# Smart Study Patterns & Distraction Analyzer (ADK Version)

This repo contains a Colab-based ADK implementation of the Smart Study Patterns & Distraction Analyzer agent.

## Structure
- `notebooks/Smart_Study_ADK_Version.ipynb` — Colab notebook with end-to-end pipeline.
- `agents/` — Agent module code.
- `tools/` — Deterministic tool modules.
- `data/` — Sample dataset and generated agent report.

## How to run (Colab)
1. Open `notebooks/Smart_Study_ADK_Version.ipynb` in Colab.
2. Install packages: `!pip install google-genai adk` (adk optional).
3. Add your `GOOGLE_API_KEY` to the environment (or Colab secrets).
4. Run all cells top-to-bottom.
5. `data/agent_report.json` will be generated.

## Notes
- This notebook includes an ADK simulation fallback if the `adk` package is not available in the environment.
- All data in this repository is synthetic for privacy.

## License
MIT
