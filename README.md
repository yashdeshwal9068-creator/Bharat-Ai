# Bharat AI — Futuristic Indian AI Assistant

Bharat AI is a highly optimized, single-file Progressive Web App (PWA) designed to deliver a blazing-fast, secure, and beautiful AI chat experience. Built specifically with minimal dependencies to run smoothly across all devices, including low-powered systems and smart TVs.

## 🚀 Features
- **Dual Provider Support:** Seamlessly switch between **Groq AI** and **OpenRouter** keys.
- **PWA Ready:** Can be installed directly as a native app on Mobile, Tablet, and Android/Smart TVs.
- **Secure Authentication:** Integrated with Firebase Auth for personal user accounts.
- **Futuristic UI:** Cyberpunk Indian aesthetic with responsive sidebar, chat history, and dark mode.

## ⚙️ Configuration Guide

You can configure your preferred AI provider directly through the **In-App Settings (⚙️)** icon without editing the code:

### Option 1: Using Groq AI (Default)
- **API Key:** Enter your Groq API Key (`gsk_...`)
- **Endpoint URL:** `https://api.groq.com/openai/v1/chat/completions`
- **AI Model Identifier:** `llama-3.3-70b-versatile` or `mixtral-8x7b-32768`

### Option 2: Using OpenRouter (Free/Paid Models)
- **API Key:** Enter your OpenRouter API Key (`sk-or-v1-...`)
- **Endpoint URL:** `https://openrouter.ai/api/v1/chat/completions`
- **AI Model Identifier:** `google/gemini-2.5-flash` or `meta-llama/llama-3-8b-instruct:free`

## 🛠️ Tech Stack
- HTML5, CSS3 (Custom Glassmorphism Utilities)
- Vanilla JavaScript (Async/Await Fetch Architecture)
- Firebase Authentication SDK
