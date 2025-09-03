# Streamlit Text Redaction App - Modern Version

A modernized version of the Streamlit text redaction application using the latest versions of Python 3.13.3, Poetry 2.1.4, Streamlit 1.49+, and LangChain 0.3+.

## Features

- Rewrite text in different tones (Formal/Informal)
- Convert text to different English dialects (American/British)
- Clean, simple Streamlit interface
- Modern dependency stack for better performance and security

## Requirements

- Python 3.13.3 or higher
- Poetry 2.1.4 or higher

## Installation

1. Navigate to the project directory:
```bash
cd new-version
```

2. Install dependencies:
```bash
poetry install
```

## Usage

1. Start the Streamlit application:
```bash
poetry run streamlit run main.py
```

2. Open your browser to the displayed URL (typically http://localhost:8501)

3. Enter your OpenAI API key when prompted

4. Input your text and select your preferred tone and dialect

5. Get your improved, redacted text!

## Migration from Old Version

This version maintains identical functionality to the old version while using modern dependencies. See `migration_documentation.md` for detailed information about the changes made during migration.

## Key Modernizations

- **Python 3.13.3**: Latest Python version with performance improvements
- **Poetry 2.1.4**: Modern dependency management with PEP 621 compliance
- **LangChain 0.3+**: Updated to use modular `langchain-core` architecture
- **Streamlit 1.49+**: Latest Streamlit features available
