# HR-Breaker

Resume optimization tool for job postings.

## Requirements

- Python 3.10+
- pdflatex (texlive or miktex)
- Google Gemini API key

## Installation

```bash
uv sync
```

## Usage

```bash
# Set API key
export GOOGLE_API_KEY=your-key

# Run
uv run streamlit run src/hr_breaker/main.py
```
