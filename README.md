# AI Growth Studio — Deploy Guide

1. GitHub pe ek naya repo banao aur is poore folder (index.html, api/, vercel.json) ko push karo.
2. vercel.com pe jao → "Add New Project" → apna repo import karo.
3. Deploy hone se pehle: Project Settings → Environment Variables →
   Name: GEMINI_API_KEY
   Value: apni Gemini key (free: https://aistudio.google.com/apikey)
4. Deploy dabao. Vercel khud index.html ko frontend aur api/generate.js ko
   serverless function ki tarah serve karega — koi extra config nahi chahiye.
5. Apna live link (e.g. ai-growth-studio.vercel.app) khulte hi tool ready hoga,
   API key kahin bhi browser mein visible nahi hogi.
