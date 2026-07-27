# VoltMatrix AI

Build and deploy your AI Studio app.

This project contains everything you need to run your app locally.

## View in Google AI Studio

https://ai.studio/apps/b8390c46-8d3f-46ab-b71f-c19805b1cad4

## Run Locally

### Prerequisites

- Node.js (v18 or later recommended)

### Installation

1. Install project dependencies:

```bash
npm install
```

2. Create a `.env.local` file in the project root and add your Gemini API key:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

Replace `YOUR_GEMINI_API_KEY` with your actual Gemini API key.

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and visit the URL displayed in the terminal (usually `http://localhost:5173` or similar).

## Project Structure

```
voltmatrix-ai/
├── src/
├── public/
├── package.json
├── .env.local
└── README.md
```

## Requirements

- Node.js
- npm
- Gemini API Key

## License

This project is for educational and research purposes.