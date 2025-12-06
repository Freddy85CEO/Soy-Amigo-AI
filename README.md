# Soy-Amigo-AI
## ✨ Features
A bilingual (Spanish/English) AI assistant designed to help Spanish-speaking users with translations, health tips, education support, and everyday questions. 
 **Bilingual Support (English & Spanish)** – Designed for Hispanic users who prefer Spanish guidance.
- **Translations** – Quickly translate documents, letters, and messages.
- **Well-Being Guidance** – Health, lifestyle, and daily life advice.
- **Education Help** – Homework support, learning explanations, and simple breakdowns.
- **Conversation Mode** – Ask general questions or get everyday help.
- **Clean UI** – Friendly design built using Lovable AI, React, and TailwindCSS.
- **Supabase Integration** – Handles backend functions and future data storage.

- ## 🛠 Tech Stack
- **React + TypeScript** – Core framework for building the interface.
- **TailwindCSS** – Utility-first styling for a clean and modern UI.
- **Supabase** – Backend services, database, and authentication.
- **Lovable AI** – Used to generate UI components and accelerate development.
- **Vite** – Fast build tool and development server.

## 📁 Project Structure

soy-amigo-ai/
├── public/                 # Static assets and icons
├── src/
│   ├── pages/              # Main page components (ex: index.tsx)
│   ├── components/         # UI components (ChatHeader, ChatMessage, etc.)
│   ├── hooks/              # Custom logic and chat hooks
│   ├── assets/             # Background images, patterns, UI graphics
│   ├── styles/             # Global styles (Tailwind)
│   └── supabase/           # Database & backend functions
├── .env                    # Environment variables
├── package.json            # Project dependencies
├── README.md               # Project documentation
└── vite.config.ts          # Vite configuration file

## ⚙️ Installation & Running Locally

Follow these steps to run the project on your machine:

### 1️⃣ Clone the repository
git clone https://github.com/Freddy85CEO/Soy-Amigo-AI.git
cd Soy-Amigo-AI

### 2️⃣ Install dependencies
npm install

### 3️⃣ Set up environment variables
Create a `.env` file in the root of the project:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

### 4️⃣ Start the development server
npm run dev

Your app will start at:

👉 http://localhost:5173/

## 🚀 Deployment

You can deploy this project using any modern frontend hosting service. Recommended options:

### 1️⃣ Deploy to Vercel (Recommended)
Vercel works beautifully with React + Vite.

Steps:
1. Go to https://vercel.com
2. Import your GitHub repository  
3. Vercel will auto-detect Vite
4. Click **Deploy**
5. Your site will be live in less than a minute

### 2️⃣ Deploy to Netlify
1. Go to https://netlify.com
2. Click **Add New Site**
3. Choose **Import from GitHub**
4. Select your repository and deploy

### 3️⃣ GitHub Pages (Simple Option)
If you want a free and simple deployment:

1. Install GH Pages:

2. Add these scripts to package.json:

```json
"homepage": "https://Freddy85CEO.github.io/Soy-Amigo-AI",
"scripts": {
  ...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

3. Deploy the site:

```bash
npm run deploy
```

Your website will be live at:

👉 https://Freddy85CEO.github.io/Soy-Amigo-AI

## 📸 Screenshots

_Add screenshots of your project here to show the UI and features._

### 🖼 Home Screen
![Home Screen](./screenshots/home.png)

### 💬 Chat Interface
![Chat Interface](./screenshots/chat.png)

### 📱 Mobile View
![Mobile View](./screenshots/mobile.png)


## 🧭 Roadmap

- [ ] Add user authentication
- [ ] Add saved chat history
- [ ] Add voice input support
- [ ] Expand bilingual educational tools
- [ ] Add mobile app version
- [ ] Deploy Supabase-based backend features





