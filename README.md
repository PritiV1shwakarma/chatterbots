<div align="center">
  <img width="1200" height="475" alt="ChatterBots Banner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />

  # 🤖 ChatterBots

  An AI-powered chat app built with Google AI Studio and the Gemini API.

  [View in AI Studio](https://ai.studio/apps/bundled/chatterbots)
</div>

---

## 📖 About

ChatterBots is an AI chatbot application powered by the **Gemini API**. [Add one or two lines about what your bots do, e.g. who they talk to and what problem they solve.]

## ✨ Features

- 💬 Real-time AI chat powered by Gemini
- [Feature 2]
- [Feature 3]
- [Feature 4]

## 🛠️ Tech Stack

- **AI:** Google Gemini API
- **Platform:** Google AI Studio
- **Runtime:** Node.js
- [Frontend framework, e.g. React / Vite]
- [Styling, e.g. Tailwind CSS]

## 🚀 Run Locally

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- A Gemini API key from [Google AI Studio](https://aistudio.google.com/)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/chatterbots.git
   cd chatterbots
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Add your API key**

   Create a `.env.local` file in the project root and add:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Start the app**
   ```bash
   npm run dev
   ```

5. Open the local URL shown in your terminal (usually `http://localhost:3000` or `http://localhost:5173`).

## 🔐 Environment Variables

| Variable | Description |
| --- | --- |
| `GEMINI_API_KEY` | Your Gemini API key from Google AI Studio |

> ⚠️ Never commit `.env.local` or your API key to GitHub. Make sure `.env.local` is listed in `.gitignore`.

## 📁 Project Structure

```
chatterbots/
├── src/            # Source code
├── public/         # Static assets
├── .env.local      # Your API key (not committed)
├── package.json
└── README.md
```

## 🌐 Deployment

You can view and run the app directly in [Google AI Studio](https://ai.studio/apps/bundled/chatterbots). To deploy your own copy, build it with:

```bash
npm run build
```

and host the output on a platform like Netlify or Vercel. Add `GEMINI_API_KEY` in the platform's environment variable settings.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and open a pull request.

## 👩‍💻 Author

Built by **Priti** ([Pricodin](https://github.com/pritivish07025))

---

⭐ If you like this project, give it a star!
