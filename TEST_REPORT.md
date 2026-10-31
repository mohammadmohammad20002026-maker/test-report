# Local QA report: BelMasry AI | بالمصري — v1.0.0

- **Date:** 2026-10-23 (system date reference).
- **Runtime:** Python 3.13.5 on Linux container, UTF-8.
- **Result:** PASS — 19 / 19 local unit/integration cases.
- **Run:** `python -m unittest discover -s tests -v`.
- **Demo command:** `python scripts/belmasry.py generate --product examples/product.json --outdir demo_outputs`.
- **Demo exit code:** 0; demonstration output captured and checked.
- **Actual generated demo files:** campaign.json, egyptian_captions.md, verified_localization.json.
- **Failure scenarios:** validated intentionally incorrect or unsupported inputs where covered by the suite.
- **Security posture:** no API keys, credentials, automatic network posting, or external requests in bundled scripts.
- **Windows PowerShell:** launch scripts included, but **not executed** in this Linux test environment.
- **Agent reasoning/localization quality:** host-model real-world conversational QA **not verified** in this environment.
- **Capafy acceptance/runtime:** not uploaded, not submitted and **not tested** inside Capafy; acceptance is not guaranteed.

## What these tests do not prove
Free-form creative translation uses the agent host; mechanical checks are not legal compliance checks or a proof of semantic truth. No social posting or image/video generation.

The tests validate implemented Python logic, supported example end-to-end command flows, file output and selected error handling. Real host-model conversational quality and every language/syllabus/job market scenario still require user acceptance testing.
