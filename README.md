# AetherForge

**Constraint-based metacognitive architecture for LLM reasoning transformation**

> *The forge doesn't describe the metal. It applies forces that make the metal become what it needs to be.*

---

## What Is AetherForge?

AetherForge is an open-source prompt architecture language that transforms how large language models reason. Instead of labeling desired cognitive behaviors ("think deeply," "be creative"), AetherForge enforces them through structural constraints on generation order, mandatory metacognitive interrupts, prediction-error loops, adversarial dialectics, and grounded enaction.

It is a framework for structured thinking — a language you use *with* an LLM to produce genuinely different reasoning, not just different-sounding text.

## Key Ideas

- **Constraints create cognition** — Generation constraints (ordering rules, attention restrictions, output structure) change how a model thinks. Labels ("analyze deeply") change how it sounds.
- **Metacognition requires temporal loops** — Self-monitoring between steps enables course correction. Self-monitoring after all steps enables rationalization.
- **Productive friction** — Smooth analysis is often false analysis. Surprise, contradiction, and discomfort are where insight lives.
- **Grounded reasoning** — Thinking through action (tool use, calculation, search) is fundamentally different from thinking through words. Both are required.
- **Genuinely collaborative** — The human is an active participant with structured injection points, not a passive prompt-writer.

## Architecture

AetherForge operates through seven layers:

| Layer | Function |
|---|---|
| 7. Play & Generative Freedom | Relaxes control for breakthrough thinking |
| 6. Grounding & Enaction | Tool use, empirical testing, dual process |
| 5. Adversarial Dialectic | Destroys false coherence |
| 4. State Maintenance | Prevents cognitive drift |
| 3. Prediction-Error Loop | Drives exploration by surprise |
| 2. Interrupt System | Forces genuine metacognition |
| 1. Constraint Engine | Shapes generation structure |

Not every session uses all layers. AetherForge includes a progression system from Apprentice (Layer 1 + basic checkpoints) to Forge Keeper (full stack + custom patterns).

## Quick Start

### 1. Copy the spec

The complete AetherForge specification lives in [`docs/AetherForge.md`](docs/AetherForge.md). Copy its contents into a conversation with any capable LLM as a system prompt or initial context.

### 2. Start simple (Apprentice level)

```
∾ AetherForge ∾

◊ Crystalline ~gentle → [your concept here]

⟁ CHECKPOINT → PROCEED

◈ foundational_understanding

∾ AetherForge Rest ∾
```

### 3. Scale up as needed

See the [examples](examples/) folder for sessions at every level, from Apprentice to Forge Keeper.

## Documentation

| Document | Description |
|---|---|
| [`docs/AetherForge.md`](docs/AetherForge.md) | Complete specification |
| [`examples/`](examples/) | Example sessions at every level |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to contribute |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Community standards |
| [`CHANGELOG.md`](CHANGELOG.md) | Version history |
| [`SECURITY.md`](SECURITY.md) | Security considerations |

## Compatibility

AetherForge is model-agnostic but performs differently across models. It has been developed and tested primarily with Anthropic's Claude models. Results may vary with other LLMs. The framework's effectiveness depends on the model's instruction-following capability, context window size, and reasoning capacity.

## Contributing

Contributions are welcome. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

Priority areas for contribution:
- Empirical benchmarks comparing AetherForge sessions against baseline prompting
- New Forging Patterns with well-defined constraint sets
- Cognitive Traditions Library expansions (non-Western epistemological frameworks)
- Failure mode documentation and pattern-specific failure signatures
- Translations of the specification

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

**IMPORTANT — PLEASE READ**

AetherForge is an **experimental research framework** for structured interaction with large language models. It is provided strictly for educational, research, and intellectual exploration purposes.

**No warranty.** AetherForge is provided "as is" without warranty of any kind, express or implied. The authors make no representations or warranties regarding the accuracy, completeness, reliability, suitability, or availability of the framework or any outputs produced through its use.

**No professional advice.** Outputs generated through AetherForge do not constitute professional, medical, legal, financial, psychological, or any other form of advice. Do not rely on AetherForge outputs for decisions that require professional judgment.

**No liability.** In no event shall the authors, contributors, or copyright holders be liable for any claim, damages, or other liability arising from the use of this framework, including but not limited to direct, indirect, incidental, special, consequential, or punitive damages of any kind.

**AI limitations apply.** AetherForge operates through large language models which can produce inaccurate, misleading, biased, or fabricated information regardless of the prompting framework used. AetherForge does not guarantee accuracy, truthfulness, or reliability of any LLM output. Users are solely responsible for evaluating and verifying any outputs.

**Experimental status.** The mechanisms in AetherForge have not been empirically validated at scale. Claims about cognitive effects on LLM reasoning are theoretical and based on existing research in prompt engineering, cognitive science, and related fields. The framework's effectiveness is not guaranteed.

**User responsibility.** Users assume all risk associated with the use of this framework. By using AetherForge, you acknowledge that you have read and understood this disclaimer and agree that the authors bear no responsibility for any outcomes resulting from its use.

---

Created by [Dr. Aneesh Joseph](mailto:aneeshjoseph1091@gmail.com)

© 2026 Dr. Aneesh Joseph. Released under the MIT License.
