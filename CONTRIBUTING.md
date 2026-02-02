# Contributing to AetherForge

Thank you for your interest in improving AetherForge. This document explains how to contribute effectively.

## How to Contribute

### Reporting Issues

Open an issue if you find:
- A mechanism that consistently fails (see Failure Signatures in the spec)
- Contradictions or ambiguities in the specification
- Missing edge cases in constraint definitions

Include: the mechanism involved, the LLM used, the input, and what went wrong.

### Proposing New Mechanisms

New Forging Patterns, Instruments, Cognitive Traditions, or Advanced Mechanisms are welcome. A good proposal includes:

1. **Name and purpose** — What cognitive operation does it force?
2. **Constraint set** — Specific generation constraints (not just descriptions). Each constraint must define what the model *must do*, not what it *should be*.
3. **Failure signature** — What does it look like when this mechanism fails?
4. **Example session** — At least one worked example showing the mechanism in use.
5. **Theoretical basis** — What research or reasoning supports this mechanism?

### Empirical Validation

The highest-value contributions are empirical:
- Run the same analytical question through AetherForge and through direct prompting
- Compare outputs using specific quality metrics (accuracy, novelty, nuance, self-correction)
- Document which layers and mechanisms contributed and which were inert
- Report across multiple models if possible

### Cognitive Traditions Library

Expansions of the Cognitive Traditions Library are especially welcome. Contributions should:
- Represent a genuine epistemological tradition (not a surface-level appropriation)
- Include specific constraints that force the tradition's mode of reasoning
- Cite sources for the tradition's core methods
- Include guidance on when this tradition is most appropriate

## Contribution Process

1. Fork the repository
2. Create a branch (`feature/your-mechanism-name` or `fix/issue-description`)
3. Make your changes
4. Ensure the specification remains internally consistent
5. Submit a pull request with a clear description of what you've added and why

## Style Guidelines

- **Constraints over descriptions.** Every mechanism must define what the model is forced to do, not just what kind of thinking is desired.
- **Failure signatures required.** If you can't describe what failure looks like, the mechanism isn't well-defined enough.
- **Token efficiency.** The specification is already large. New additions should be concise. If a mechanism can be expressed in fewer words without losing precision, use fewer words.
- **No ungrounded claims.** Don't claim a mechanism "achieves genuine metacognition" or "creates consciousness." Describe what it does structurally and let users evaluate the results.

## Code of Conduct

All contributors are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
