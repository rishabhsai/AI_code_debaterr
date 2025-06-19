# 🤖💎 AI Code Debate

An interactive code generation system where two AI models debate and refine code through multiple rounds of discussion until they reach agreement on the optimal solution.

## 🎯 Overview

AI Code Debate creates a collaborative environment where:
- **GPT-4o mini** acts as the **Coder** - generates and refines code
- **Gemini 1.5 Flash** acts as the **Reviewer** - provides detailed critiques and suggestions
- Both models iterate through multiple rounds until they agree on the final solution

## ✨ Features

- 🔄 **Multi-round debate system** with configurable rounds (1-5)
- 📝 **Real-time conversation logging** with full debate transcripts
- 📄 **PDF export** of complete debate sessions
- 🎨 **Clean Gradio web interface** for easy interaction
- 💻 **Syntax highlighting** for generated code
- 📚 **Example prompts** for common coding tasks
- ⚡ **Fast response times** using optimized cloud APIs

## 🚀 Quick Start

### Prerequisites
- Google Colab account
- OpenAI API key
- Google AI Studio API key (Gemini)

### Setup

1. **Get API Keys:**
   - OpenAI: Get your key from [OpenAI Platform](https://platform.openai.com/api-keys)
   - Gemini: Get your key from [Google AI Studio](https://aistudio.google.com/app/apikey)

2. **Configure Secrets in Colab:**
   - Click the key icon (🔑) in the left sidebar
   - Add `OPENAI_API_KEY` with your OpenAI key
   - Add `GEMINI_API_KEY` with your Gemini key
   - Enable "Notebook access" for both

3. **Run the Code:**
   - Copy the provided code into Google Colab
   - Run Cell 1 (Setup)
   - Run Cell 2 (Main Application)
   - Click the generated public URL
