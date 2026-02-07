# Gating Signal Dataset

Goal: collect **sanitized** examples of platform gating signals (rate limits, verification, captchas, bans).

Rules:
- Do NOT include secrets/tokens.
- Prefer minimal, reproducible excerpts (status code + a few headers + a short body snippet).
- Never include copy/pastable exploit commands.

Contribute samples under `datasets/gating-signals/samples/` (one JSON per sample).
