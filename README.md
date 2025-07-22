# 🧠 AI Image Generator (Text-to-Image + Animation) | GenAI Project

## 🖼️ Screenshot
![App Screenshot](https://i.ibb.co/GsDnTKp/3044dbc1-b729-4438-b7dc-7bcfc6ec7d33.png)


A Next.js frontend app that generates images from text prompts using **Gemini Flash API**, with optional animation via **Fal API** (paid).

## 🧩 Tech Stack

- Next.js + TypeScript
- Tailwind CSS
- ShadCN UI
- Gemini Flash API (Text → Image)
- Fal API (Image → Animation, optional)

## 🔄 Flow

1. User enters a text prompt  
2. Gemini API returns image  
3. User views/downloads  
4. (Optional) Animation via Fal API

## 🚀 Getting Started

```bash
# 1. Clone & Install
npm install

# 2. Set API Keys
echo "NEXT_PUBLIC_GEMINI_API_KEY=your_key" >> .env.local
echo "NEXT_PUBLIC_FAL_API_KEY=your_key" >> .env.local

# 3. Run App
npm run dev
