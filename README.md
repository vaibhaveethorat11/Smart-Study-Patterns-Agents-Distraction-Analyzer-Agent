# Smart Study Patterns & Distraction Analyzer (ADK-style)

This repository contains the Colab-ready ADK-style multi-agent capstone:
- **Gemini 1.5 Flash** LLM for reasoning (free via Google GenAI)
- **ADK-style simulation**: Analyzer, Distraction Detector, Coach, Coordinator
- Realistic synthetic dataset generator (privacy-first)
- EDA, multi-agent pipeline, and generated report

## Contents
- `notebooks/Smart_Study_ADK_Version.ipynb` — Colab notebook (main)
- `agents/` — optional agent modules (refactor if desired)
- `tools/` — deterministic helper tools
- `data/study_data.csv` — generated sample dataset
- `agent_report.json` — sample output from a run

## Quickstart (Colab)
1. Open `notebooks/Smart_Study_ADK_Version.ipynb` in Google Colab.
2. Add your Gemini API key to Colab Secrets as `GEMINI_API_KEY`.
3. Run all cells top-to-bottom.
4. `agent_report.json` will be produced in the working directory.

## Safety & Privacy
- All example data is synthetic by default.
- **Do not** commit API keys. Use Colab or GitHub Secrets.

## Files to review
- `notebooks/Smart_Study_ADK_Version.ipynb` — main demo
- `agent_report.json` — end-of-run report
- `README.md` — this file

## Future Work
- Add persistent memory for long-term personalization
- Add optional user-uploaded logs handler
- Create a lightweight frontend (optional)

## License
MIT
