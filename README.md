<h1 align="center">Niite Bot</h1>

<p align="center">
  A versatile Telegram bot powered by AI for image generation, information retrieval, and entertainment
</p>

## 🌟 Overview

Niite Bot is a feature-rich Telegram bot that combines AI capabilities with utility functions to provide a seamless user experience. Built with Node.js and modern APIs, it offers everything from AI image generation to real-time information services.

## ✨ Features

### AI & Image Generation
- Image generation using multiple Hugging Face models
- Smart model selection for different art styles
- Image regeneration and customization options

### Information Services
- Real-time timezone information
- Currency conversion
- Random facts with relevant images
- Joke generation
- Reddit meme integration

### Admin Features
- Maintenance mode management
- User activity monitoring
- Broadcasting capabilities
- System statistics and analytics
- Command usage tracking

## 🛠 Technical Stack

- **Runtime**: Node.js
- **Main Dependencies**:
  - node-telegram-bot-api
  - @huggingface/inference
  - @google/generative-ai
  - moment-timezone
  - natural (NLP)
  - dotenv

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Create a `.env` file with required credentials:
```env
TELEGRAM_BOT_TOKEN=your_token
HUGGING_FACE_TOKEN=your_token
GOOGLE_AI_API_KEY=your_key
ADMIN_USER_ID=your_admin_id
```
4. Start the bot:
```bash
node bot.js
```

## 📝 Environment Variables

- `TELEGRAM_BOT_TOKEN`: Your Telegram bot token
- `HUGGING_FACE_TOKEN`: Hugging Face API token
- `GOOGLE_AI_API_KEY`: Google AI API key
- `ADMIN_USER_ID`: Telegram user ID for admin access
- `UNSPLASH_ACCESS_KEY`: Unsplash API key (optional)
- `PIXABAY_API_KEY`: Pixabay API key (optional)
- `NINJA_API_KEY`: API Ninjas key (optional)

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the ISC License.

## 👤 Author

Hi, My name is Arane Aimer.
I am a self-taught full-stack developer, entrepreneur working on useful and innovative applications. I started this project as a hobby to learn more about AI and to implement action models in real world applications.

Upcoming Projects:
- Prism - A privacy first, versatile productivity tool; Notes, Tasks, Calendar, Chat, Project Management and much more combined with the objective to build a personal assistant AI for everyone.