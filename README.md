# promptshield
PromptShield — Detecting Prompt Injection Before It Reaches Your LLM

Why: LLM apps are vulnerable to instruction override, data exfiltration, and obfuscation.
What: A lightweight pre-filter that returns a risk score (0–1) + human-readable reasons.
How: Heuristics (override phrases, homoglyphs/zero-width, base64) + ML (TF-IDF + Logistic).
Status: Data schema ✅ | Seed dataset 🚧 | Heuristics 🚧 | Baseline model ⏳ | API ⏳
