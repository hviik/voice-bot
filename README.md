# Cohere Voice Bot 🎤

A sophisticated voice bot that responds as Cohere AI would, built with modern web technologies and designed for easy deployment on Vercel.

Note: Used Cohere instead of OpenAI due to the limitations of the free tier with OpenAI.

## 🚀 Features

- **Voice Recognition**: Natural speech-to-text using Web Speech API
- **Cohere AI Responses**: Authentic responses that match Cohere's personality and knowledge
- **Text-to-Speech**: AI responds with voice synthesis
- **Modern UI**: Elegant dark theme with glassmorphic design
- **Real-time Animations**: Visual feedback during listening and processing
- **Mobile Responsive**: Works seamlessly on all devices

## 🎯 Sample Questions

The bot is designed to respond to questions like:
- "What should we know about your life story in a few sentences?"
- "What's your #1 superpower?"
- "What are the top 3 areas you'd like to grow in?"
- "What misconception do your coworkers have about you?"
- "How do you push your boundaries and limits?"

## 🛠️ Quick Deploy to Vercel

### Method 1: One-Click Deploy
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/hviik/voice-bot)

### Method 2: Manual Deploy
1. **Fork/Download** this repository
2. **Sign up** for [Vercel](https://vercel.com) (free)
3. **Connect your GitHub** account to Vercel
4. **Import** your repository
5. **Deploy** - No configuration needed!

### Method 3: Vercel CLI
```bash
# Install Vercel CLI globally
npm i -g vercel

# Deploy from project directory
vercel

# Follow the prompts, then your app will be live!
```

## 💻 Local Development

```bash
# Clone the repository
git clone your-repo-url
cd cohere-voice-bot

# Install dependencies (optional, for development server)
npm install

# Start local server (or just open index.html in browser)
npm run dev
```

## 🌐 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Edge
- ✅ Safari (limited speech synthesis)
- ❌ Firefox (limited Web Speech API support)

## 🔧 Technical Details

- **Frontend**: Pure HTML, CSS, JavaScript (no frameworks)
- **Speech Recognition**: Web Speech API
- **Text-to-Speech**: Speech Synthesis API
- **Styling**: Modern CSS with glassmorphism effects
- **Deployment**: Static site optimized for Vercel

## 🎨 Customization

The bot's personality and responses can be easily customized by modifying the `CohereResponses` object in the JavaScript code.

## 📱 Usage

1. **Click** "Ask a Question" button
2. **Speak** your question clearly
3. **Listen** to Cohere's response
4. **Repeat** for more questions!

## 🔒 Privacy

- All speech processing happens in your browser
- No data is sent to external servers
- No API keys required for basic functionality

## 🆘 Troubleshooting

- **No microphone access**: Check browser permissions
- **Speech recognition not working**: Try Chrome browser
- **No voice synthesis**: Check browser audio settings

## 📞 Support

For issues or questions, please check the browser console for error messages and ensure you're using a supported browser.

---

**Created with ❤️ for seamless AI voice interaction**