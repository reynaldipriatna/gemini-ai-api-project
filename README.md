# 🚀 Gemini AI API Endpoints (Node.js)

A minimalist Node.js project showcasing various capabilities of the Google Gemini AI API. This project provides simple API endpoints to interact with Gemini for text generation, image analysis, document summarization, and audio transcription/analysis.

## ✨ Features

- **Generate Text:** Get AI-generated text based on a given prompt.
- **Generate from Image:** Analyze an image and generate a description or answer questions about its content.
- **Generate from Document:** Process and summarize content provided as long text (simulating document content).
- **Generate from Audio:** Transcribe and/or analyze audio content.

## 📦 Technologies Used

- **Node.js:** JavaScript runtime.
- **Express.js:** Fast, unopinionated, minimalist web framework for Node.js.
- **Google Generative AI SDK:** Official Google library for interacting with Gemini API.
- **dotenv:** Loads environment variables from a `.env` file.

## 📋 Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v18.x or higher recommended)
- npm (Node Package Manager)

## 🔑 API Key Configuration

1.  **Obtain a Google Gemini API Key:**

    - Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
    - Create a new API key or use an existing one.

2.  **Create a `.env` file:**
    - In the root directory of your project, create a file named `.env`.
    - Add your API key to this file:
      ```
      GEMINI_API_KEY="YOUR_GENERATED_GEMINI_API_KEY_HERE"
      ```

## 🚀 Getting Started

Follow these steps to get your project up and running:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gemini-api-project.git
cd gemini-api-project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the project

```bash
npm start
# or
node index.js
```

The server will start on http://localhost:3000.
