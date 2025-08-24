
# 🌐 AI Translator

A desktop application that translates text between multiple languages using **OpenAI GPT-4o-mini**. Built with **Python** and **Tkinter**, providing a simple and interactive GUI.

---

## Features

- Translate text between multiple languages:
  - English, Hindi, French, Spanish, Telugu, Arabic, Japanese
- Copy translations automatically to clipboard
- Interactive GUI with language selection buttons
- Clear input/output with a single click
- Powered by **OpenAI GPT-4o-mini**

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/ai-translator.git
cd ai-translator
```

2. **Create a virtual environment** (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install openai python-dotenv
```

> Tkinter comes with Python, no installation needed separately.

4. **Set up OpenAI API key**

Create a `.env` file in the project root:

```
OPENAI_API_KEY=your_openai_api_key_here
```

---

## Usage

1. Run the application:

```bash
python translator.py
```

2. **Select source and target languages** using the buttons.

3. **Enter text** in the "Enter Text" box.

4. Click **"Translate"** to get the translation.
   - Translation appears in the output box.
   - Automatically copied to clipboard.

5. Click **"Clear"** to reset both input and output fields.

---

## Examples

### Example 1

**Input:**

```
Hello, how are you?
```

**From Language:** English  
**To Language:** Hindi  

**Output:**

```
नमस्ते, आप कैसे हैं?
```

### Example 2

**Input:**

```
Good morning
```

**From Language:** English  
**To Language:** French  

**Output:**

```
Bonjour
```

### Supported Languages

- English  
- Hindi  
- French  
- Spanish  
- Telugu  
- Arabic  
- Japanese

---

## Notes

- Ensure your OpenAI API key is valid.  
- Internet connection is required.  
- Maximum tokens per request: 500.  

---

## Troubleshooting

- **API Key Error:**  
  If the app shows an API key error, make sure `.env` exists with:
  ```
  OPENAI_API_KEY=your_openai_api_key_here
  ```
- **Empty Input Warning:**  
  Enter text before clicking "Translate".

---

## Acknowledgements

- [OpenAI API](https://openai.com/api/)  
- [Tkinter](https://docs.python.org/3/library/tkinter.html)  
- Inspired by AI-powered translation tools
