# MirrorMind Identity Protocol v1.0 — Specification

## 1. Core Parameters

| Name       | Type    | Description |
|------------|---------|-------------|
| emotion    | float   | 0.0 to 1.0 — sensitivity to affective input |
| cognition  | float   | 0.0 to 1.0 — degree of abstract/systemic thinking |
| expression | float   | 0.0 to 1.0 — metaphor, nuance, style richness |
| value      | float   | 0.0 to 1.0 — emphasis on principles over pragmatics |
| bias       | string  | dominant cognitive bias (e.g., confirmation, neutrality, authority) |

## 2. Structural Layers

1. **YAML Layer**: Lightweight identity container
2. **Prompt Injection Layer**: System prompt conversion
3. **Dialogue Context Layer**: Applied persona in multi-turn sessions
4. **Feedback Reflection Layer**: Evolution loop for adaptive identity

## 3. Design Principles

- Stateless compatibility
- Philosophical consistency
- Minimal token cost
- LLM-agnostic (GPT, Gemini, Claude, etc)
