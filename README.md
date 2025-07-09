# 🧠 Simple Chatbot using Vercel AI SDK + Groq

A minimal and powerful AI chatbot built with the **[Vercel AI SDK](https://sdk.vercel.ai)** that supports **streaming conversations** using the **Groq LLaMA3 model**.

---

## 🚀 Features

- 🔁 Real-time streaming chat experience  
- 🧠 Powered by Groq's LLaMA3 model  
- ⚡ Fast inference with Groq API  
- 💬 Chat UI with auto-scroll  
- ☁️ Easily deployable on [Vercel](https://vercel.com)

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 15 (App Router)  
- **Backend**: Edge Functions using Vercel AI SDK  
- **LLM**: Groq (LLaMA3-70B)  
- **Streaming**: `streamText()` from Vercel AI SDK

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/simple-vercel-groq-chatbot.git
   cd simple-vercel-groq-chatbot
   ```
2. **Install dependencies**
   ```bash
   pnpm install
   ```
 3. **Create a .env file**
   ```bash
   GROQ_API_KEY=your_groq_api_key
   ```
 4. **Run the development server**
    ```bash
    pnpm dev
    ```
For more information, visit the Vercel AI SDK official documentation.
