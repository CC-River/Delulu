# 💘 Virtual Cupid — *Delulu*

> **Delulu - Meet your virtual One. You will no longer be ALONE!!**

Virtual Cupid is an interactive anime-style VR dating experience built entirely in the browser. Design your perfect partner, pick a date location, and have a real AI-powered conversation — all inside an immersive 3D world.

---

## ✨ Features

- 🎨 **Anime Character Creator** — Customise gender, skin tone, hair colour, height, personality, and outfit with a live animated preview
- 🌍 **6 Immersive Date Locations** — Café, Cherry Blossom Park, Sunset Beach, Night Rooftop, Library Nook, and Night Festival
- 💬 **Live AI Chat** — Powered by the Gemini API; your partner responds in character based on their personality
- 🎭 **6 Unique Personalities** — Romantic, Kind, Funny, Intelligent, Adventurous, and Mysterious
- 🕹️ **First-Person VR Navigation** — Walk around the scene using WASD + mouse look controls
- 🌸 **Animated 3D Avatars** — Fully built in A-Frame with aura effects, floating name tags, and personality accessories
- 🏮 **Rich Scene Decorations** — Each location has unique decorative elements like cherry blossoms, city lights, lanterns, and more
- 🔁 **Scene Switching** — Change your date location on the fly without losing your conversation

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [A-Frame 1.4.2](https://aframe.io) | 3D / VR scene rendering |
| HTML / CSS / JavaScript | UI, character creator, chat interface |
| Node.js + Express | Backend server |
| Gemini API | AI-powered chat responses |
| Google Fonts | Cinzel, Dancing Script, Nunito typography |

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org) installed
- A [Gemini API key](https://aistudio.google.com)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/CC-River/Delulu.git
cd Delulu
```

2. **Install dependencies**
```bash
npm install express cors node-fetch dotenv
```

3. **Set up your API key**

Create a `.env` file in the project root:
```
GEMINI_API_KEY=your_api_key_here
```

4. **Run the server**
```bash
node server.js
```

5. **Open in browser**
```
http://localhost:3000/virtual-cupid.html
```

---

## 🎮 How to Play

1. Click **Begin Your Story** on the splash screen
2. Choose your **date location** and **relationship vibe**
3. **Design your partner** — pick their look and personality
4. Click **Start Our Date** to enter the VR scene
5. Explore using **WASD** to move and **mouse** to look around
6. Click **💬 Chat** to start talking to your partner
7. Use the **scene switcher** on the left to change locations anytime

---

## 📁 Project Structure

```
Delulu/
├── virtual-cupid.html   # Main frontend — full VR experience
├── server.js            # Node.js backend — handles Gemini API calls
├── .env                 # API key (not committed to GitHub)
├── .gitignore           # Ignores .env and node_modules
└── README.md
```

---

## ⚠️ Important

- Never commit your `.env` file — it contains your private API key
- The `.gitignore` file is already set up to protect it
- Always run `git pull origin main` before making changes if working in a team

---

