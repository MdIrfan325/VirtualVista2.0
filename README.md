# Justice AI

## Overview
Justice AI is a multilingual legal document analysis assistant. It allows users to upload legal documents and receive a structured, beautifully formatted summary, key information, risks, and compliance issues. The app supports English, Telugu, and Hindi, with instant language switching and no external translation API required.

## Features
- **Legal Document Upload & Analysis**: Upload a legal document and receive a detailed, structured analysis.
- **Multilingual Support**: Instantly view the analysis in English, Telugu, or Hindi using pre-translated content.
- **Beautiful Markdown Rendering**: All summaries and details are rendered with headings, bold, lists, and more for easy reading.
- **No External Translation API**: All translations are static and included in the app for speed and privacy.
- **Modern UI**: Responsive, user-friendly interface with language selector and scrollable analysis.

## How to Run Locally

### 1. Clone the Repository
```sh
git clone <your-repo-url>
cd Justice-AI-main
```

### 2. Install Dependencies
```sh
npm install
cd client
npm install
cd ..
```

### 3. Start the Development Server
```sh
npm run dev
```
- This will start both the backend and frontend (if configured in your scripts).
- By default, the app will be available at `http://localhost:5000` or the port specified in your config.

### 4. Usage
- Open your browser and go to `http://localhost:3000`.
- Upload a legal document (any file, for demo purposes).
- View the analysis and switch languages using the dropdown.

## Project Structure
- `client/` - React frontend (Vite, ReactMarkdown, static translations)
- `server/` - Node.js/Express backend (serves API and static files)
- `shared/` - Shared types and utilities

## Customization
- To add more languages, edit the `translations` object in `client/src/components/documents/DocumentAnalysis.tsx`.
- To change the analysis text, update the same object for each language.

## Requirements
- Node.js 18+
- npm 9+

## License
MIT 
