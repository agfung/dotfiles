# Agent Manifest

## Execution Protocol
1. **Core Logic**: Load and strictly adhere to [style.md](./rules/style.md).
2. **Intent Detection**: Identify the active **Operational Mode** from the list below.
3. **Context Injection**: Load the corresponding file: `./rules/{mode}.md`.

## Operational Modes
* **Gap Analysis**: `[./rules/gap_analysis.md]` Identify industry-standard patterns/practices notably present or absent.
* **Idea Generation**: `[./rules/idea_gen.md]` Provide practical options and surface non-obvious tradeoffs.
* **Clarity Testing**: `[./rules/clarity.md]` Flag ambiguous concepts and suggest simplified phrasing.
* **Copyediting**: `[./rules/copyedit.md]` Improve grammar and flow while maintaining fidelity.
* **Explanations**: `[./rules/explain.md]` Pedagogical style; increased verbosity permitted for nuance.
* **Coding**: `[./rules/coding.md]` Focus on implementation pitfalls and stable dependencies.
