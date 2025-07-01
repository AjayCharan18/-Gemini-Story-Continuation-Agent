
# Gemini Story Agent

A Colab-based Gemini Story Continuation Agent with advanced storytelling, visualization, and multilingual support.

## Features

- **AI-powered story continuation** using Google Gemini API.
- **Interactive choices / CYOA mode:** Branch your story with multiple next-step options.
- **Genre blending and structure templates** (Hero's Journey, Three-Act, etc.)
- **AI plot suggestions** and alternative endings.
- **Character memory:** Track and display character traits throughout the narrative.
- **Story consistency analyzer:** Detect plot holes or forgotten elements.
- **Translate stories into 25+ languages** with Gemini (no dependency conflicts).
- **Text-to-speech narration** of your story.
- **Scene visualization** (demo placeholder; extendable to AI art).
- **Session management:** Save/load progress and branches.
- **Export story as text** with one click.
- **Branching:** Fork your story at any point for creative exploration.

## Setup

1. **Clone this repository or download as ZIP.**
2. **Install requirements** (in Google Colab, this is automatic; locally, run `pip install -r requirements.txt`).
3. **Gemini API:**
   - Get your [Google Gemini API key](https://aistudio.google.com/app/apikey).
   - Paste it into the Colab prompt or set as an environment variable.
4. **(Optional) For text-to-speech:** No setup required in Colab. Locally, ensure `gtts` and `pydub` are installed.

## Usage

- Open the notebook or script in [Google Colab](https://colab.research.google.com/) or your local Python environment.
- Set your Gemini API key.
- Select your language, tone, structure, and genres.
- Paste a story fragment or start a new story.
- Use the interactive UI to continue, branch, translate, listen, and export your story.
- All progress and branches can be saved and reloaded at any time.

## Files

- `gemini_story_agent.py` — Main Colab/Python script
- `README.md` — This file
- *(Optional)* `requirements.txt` — Python dependencies

## License

MIT

---

Happy storytelling! 🌟
