# SpinBot AI - Paraphrasing Tool

A modern, AI-powered paraphrasing tool built with React, Tailwind CSS, and Google's Gemini AI.

## 🚀 Quick Start (Local Development)

1. **Clone or Download** the project files.
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Set up Environment Variables**:
   - Copy `.env.example` to `.env`.
   - Get a free Gemini API Key from [Google AI Studio](https://aistudio.google.com/app/apikey).
   - Add your key to the `.env` file: `VITE_GEMINI_API_KEY=your_key_here`.
4. **Run the App**:
   ```bash
   npm run dev
   ```

## 🌐 Deploy for Free (Vercel or Netlify)

This app is designed to be hosted for free on platforms like Vercel or Netlify.

### Vercel Deployment
1. Push your code to a GitHub repository.
2. Connect your repository to [Vercel](https://vercel.com).
3. In the **Environment Variables** section of your Vercel project settings, add:
   - Key: `VITE_GEMINI_API_KEY`
   - Value: `(Your Gemini API Key)`
4. **Build Settings** (usually automatic, but check if it fails):
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Install Command: `npm install`
5. Click **Deploy**.

### Netlify Deployment
1. Push your code to a GitHub repository.
2. Connect your repository to [Netlify](https://netlify.com).
3. In the **Site settings > Environment variables** section, add:
   - Key: `VITE_GEMINI_API_KEY`
   - Value: `(Your Gemini API Key)`
4. Trigger a new deploy.

## ✨ Features
- **5 AI Modes**: Standard, Creative, Formal, Shorten, and Expand.
- **AI Insights**: Tone analysis, readability score, and key takeaways.
- **Local History**: Your recent rewrites are saved locally in your browser.
- **Responsive Design**: Works perfectly on mobile and desktop.
- **Privacy Focused**: No server-side storage; all processing happens via API and local storage.
- **SPA Routing**: Includes `vercel.json` to ensure sub-routes work correctly on Vercel.

## ⚖️ License
This project is licensed under the Apache-2.0 License.
