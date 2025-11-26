# Luxora AI Studio

Luxora AI Studio transforms your photos into cinematic and experimental looks using Gemini models. Upload one or two subjects, tailor styles and camera angles, preview JSON prompts, and export or save to Google Drive. After the first 3 free credits, a Pro upsell encourages upgrading for unlimited renders.

## Features
- Dual subject uploads with optional negative prompts and background removal
- Text and image model selection (Gemini 3 Pro/2.5 options)
- JSON-only mode for prompt export and history search/download
- In-app Pro upsell after 3 renders
- Google Drive save (when configured)

## Quickstart
1) Install dependencies  
   ```bash
   npm install
   ```
2) Configure your key in `.env.local`  
   ```
   GEMINI_API_KEY=your-key-here
   ```
3) Run the app  
   ```bash
   npm run dev
   ```

## Notes
- Node.js 18+ recommended.
- Set Google Drive client credentials in `services/googleDriveService.ts` to enable Drive saving.
