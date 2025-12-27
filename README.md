# Tamil-English Slang Translator 🗣️

<img width="999" height="929" alt="tamil1" src="https://github.com/user-attachments/assets/4cd8187b-ccd6-469f-aecc-cba52ffb7112" />


A local guide tool that translates Tamil slang (urban + village) into clear English explanations, powered by Kiro AI.

## Problem Statement

Tamil slang is rich, contextual, and constantly evolving. From Chennai's urban "mass da" to village expressions like "sothapuna case", these phrases carry cultural nuances that standard translators miss. This tool bridges that gap.

## Solution

A simple chat-based translator that:
- Understands Tamil slang from both urban and rural contexts
- Provides clear English explanations with cultural context
- Uses a custom `product.md` file to teach Kiro about local nuances

## Features

- Real-time slang translation
- Cultural context explanations
- Support for both urban and village Tamil expressions
- Simple web interface

## Tech Stack

- Python (Flask)
- HTML/CSS/JavaScript
- Kiro AI with custom context

## Quick Start

### Download ZIP File

1. **Download** the `tamil-slang-translator.zip` file from this repository
2. **Extract** the ZIP file to your desired location
3. **Navigate** to the extracted folder:
   ```bash
   cd tamil-slang-translator
   ```
4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Run the application**:
   ```bash
   python app.py
   ```
6. **Open browser** at `http://localhost:5000`

## Project Structure

```
tamil-slang-translator/
├── .kiro/
│   └── steering/
│       └── product.md          # Custom context for Tamil slang
├── app.py                       # Flask backend
├── templates/
│   └── index.html              # Chat UI
├── static/
│   └── style.css               # Styling
├── requirements.txt            # Dependencies
├── README.md                   # This file
```

## Example Translations

- "mass da" → "That's awesome/cool, bro!"
- "vera level" → "Next level, extraordinary"
- "sothapuna case" → "A messed up situation"

## How Kiro Accelerated Development

This project was built with Kiro AI assistance, which:
- Understood Tamil cultural context through custom product.md
- Generated the complete application structure
- Provided culturally-aware translations
- Accelerated development from concept to working prototype

## Submission

- **GitHub Repository**: https://github.com/MakendranG/Tamil-English-Slang-Translator-
- **AWS Builder Center Blog**: [Your blog link]
- **Theme**: The Local Guide
- **Challenge**: AI for Bharat

---

Built with ❤️ for Tamil culture
