# Readify - Dyslexia-Friendly Reading Tool

Readify is an AI-powered web application designed to make reading more accessible and enjoyable for individuals with dyslexia. By providing dyslexia-friendly formats, text-to-speech capabilities, and AI-driven text refinement, this tool ensures a comfortable and inclusive reading experience.

"Read Better. Live Brighter. For Dyslexia."

## Features

- **Dyslexia-Friendly Formats**: Converts standard text into readable, dyslexia-friendly fonts and layouts.
- **PDF Upload & Processing**: Seamlessly upload PDF documents to extract and adapt text.
- **Text-to-Speech (TTS)**: Integrated with Google TTS API to read text out loud.
- **AI Text Refinement**: Utilizes OpenAI to simplify or adjust complex text for better comprehension.
- **Modern Interface**: Built with Next.js, Tailwind CSS, and Radix UI primitives for a highly accessible, responsive, and beautiful user experience. 

## Tech Stack

- **Frontend**: [Next.js 15](https://nextjs.org/) (App Router), React 19, Tailwind CSS
- **UI Components**: [Radix UI](https://www.radix-ui.com/) (configured via `shadcn/ui` style patterns)
- **Integrations**: `openai`, `google-tts-api`, `pdf-parse`, `pdfjs-dist`

## Getting Started

First, ensure you have your environment variables set up (e.g., your OpenAPI key for AI text processing).

Then, install dependencies and run the development server:

```bash
npm install
npm run dev
# or use yarn / pnpm / bun
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage
1. Navigate to the landing page at `/`.
2. Click **Go** to proceed to the document tools.
3. Upload a document (PDF) or interact with the text.
4. View the refined text in a dyslexia-friendly format and use the text-to-speech controls as needed.


