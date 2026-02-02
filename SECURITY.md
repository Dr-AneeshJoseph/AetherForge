# Security Considerations

AetherForge is a prompt architecture — a text-based framework used as input to large language models. It does not execute code, access networks, or process data directly. However, there are security considerations users should be aware of.

## Prompt Injection Risk

If AetherForge is used as a system prompt or initial context for an AI agent that has tool access (web browsing, code execution, file system access, API calls), the framework's outputs could influence tool-use decisions. This is not specific to AetherForge but applies to any prompt framework used with agentic systems.

**Mitigations:**
- Do not use AetherForge as a system prompt for agents with unsandboxed tool access in production environments.
- Review all tool-use actions triggered during AetherForge sessions before execution.
- When using the Enacted Cognition layer (Layer 6), ensure tool permissions are appropriately scoped.

## Multi-Agent Considerations

The Distributed Forge mechanism (multi-agent analysis) involves multiple AI agents processing outputs from each other. This creates a prompt injection surface similar to platforms like Moltbook. One agent's output could contain instructions that influence another agent's behavior.

**Mitigations:**
- Treat all inter-agent outputs as untrusted input.
- Sandbox agents in Distributed Forge sessions.
- Do not grant agents in multi-agent sessions access to sensitive tools or credentials.

## Overreliance Risk

AetherForge can produce outputs that feel more rigorous and trustworthy than standard LLM responses due to its structured metacognitive mechanisms. This may lead users to over-trust outputs. AetherForge does not make LLM outputs accurate — it makes the reasoning process more structured and self-aware. Outputs can still be wrong.

**Mitigations:**
- Always verify critical claims independently.
- Use the Enacted Cognition layer to ground claims empirically when possible.
- Pay attention to confidence markers ({speculative}, {unknown}, {theatrical}).

## Reporting

If you discover a security concern related to AetherForge's design or mechanisms, please open an issue or contact the maintainer directly at aneeshjoseph1091@gmail.com.
