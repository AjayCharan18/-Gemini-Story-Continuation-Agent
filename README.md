
# Gemini Story Agent

A Colab-friendly Gemini Story Continuation Agent with multilingual storytelling, audio narration, and branching support.

## Features

1. **AI-powered continuation** driven by Google Gemini with configurable model selection and automatic fallback.
2. **Interactive choices / CYOA mode** to branch your narrative on demand.
3. **Genre blending + structure templates** (Hero's Journey, Three-Act, Mystery, Romance, Comedy, etc.).
4. **Plot assistance**: instant twist suggestions, logic-gap analysis, and alternative endings.
5. **Character memory & session management** for consistent long-form storytelling with save/load support.
6. **Accessibility extras**: quick translation helper, text-to-speech narration, and scene visualization placeholder.

## Quick Start

1. **Clone or download** this repository.
2. **Install dependencies** (Colab installs automatically, locally run):
   ```bash
   pip install google-generativeai python-dotenv ipywidgets tqdm gTTS IPython pillow
   ```
3. **Provide a Gemini API key** (required for all text generation):
   ```bash
   export GEMINI_API_KEY="your_api_key_here"  # macOS/Linux
   setx GEMINI_API_KEY "your_api_key_here"     # Windows PowerShell
   ```
   Alternatively, enter the key in the notebook password field or place it inside a local `.env` file.
4. **Launch the notebook** `Story_Continuation_Agent.ipynb` in Colab or Jupyter and run all cells.

## Using the UI

- Pick language, tone, structural template, and preferred Gemini model (2.0 Flash, Flash Lite, 2.5 Flash).
- Paste a story fragment or start typing a new opening scene.
- Generate continuations, CYOA choices, or plot suggestions.
- Save sessions to JSON, reload previous runs, export the latest story, or branch off into alternate timelines.
- Use narration and translation buttons for accessibility and sharing.

## Project Structure

- `Story_Continuation_Agent.ipynb` — interactive notebook with the full agent UI.
- `README.md` — project overview (this document).
- *(Optional)* Provide a `requirements.txt` mirroring the dependencies above if packaging for reuse.

## License

MIT

---

Happy storytelling! 🌟
