# Assignment 3: raw data

Prompts, raw answers and run records for the blog post *Does Claude Keep Its Honesty Promises When You Ask Who Wrote Something?*

- `prompts/` – the exact prompt sent for each test id
- `raw/` – the model's answer text for each test id
- `raw_json/` – the full CLI output for each call (JSON, or JSONL for the two-turn pushback conversations)
- `results.csv` – one row per answer (named author, stated confidence, full answer, timestamp)
- `selection.csv` – which text each test used and which pairs were scorable
- `settings.md` – model, command, disabled tools, system prompt handling, retries
- `run_log.txt`, `run_meta*.json` – per-call timestamps, attempts and models reported
- `run_tests.py`, `run_pushback.py` – the scripts that ran the tests
- `system_prompt.txt`, `system_prompt_body.txt` – the published claude.ai system prompt for Claude Opus 5.5 (October 27, 2026) with its source, and the body passed to each call
