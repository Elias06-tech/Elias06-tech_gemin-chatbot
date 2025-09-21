# Google Colab Gemini Chatbot

A powerful AI chatbot built with Google's Gemini AI, designed for Google Colab with secure API key management.

## 🌟 Features

- Interactive chatbot with conversation memory
- Customizable AI personalities
- Chat history tracking
- Multiple chatbot modes (basic and enhanced)
- Secure API key management
- Comprehensive error handling and troubleshooting

## 🚀 Quick Start

### 1. Get Your API Key
- Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
- Create a new API key
- Copy the key (starts with 'AIza')

### 2. Run in Google Colab
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the chatbot.ipynb file
3. Run all cells
4. Enter your API key when prompted

### 3. Start Chatting
python
# Try these commands:
run_enhanced_chatbot()        # Full-featured chatbot
ask_gemini("Hello there!")    # Single question


## 📋 Available Functions

| Function | Description |
|----------|-------------|
| run_enhanced_chatbot() | Interactive chat with personalities |
| run_chatbot() | Basic chatbot mode |
| ask_gemini(question) | Single question function |
| diagnose_api_issue() | Troubleshoot API problems |
| test_simple_request() | Test API connectivity |

## 🎭 Chatbot Commands

While chatting, use these commands:
- quit, exit, bye - End conversation
- history - Show chat history
- clear - Clear screen
- personality [description] - Set AI personality
- help - Show help message

## 🔒 Security

This project uses environment variables to protect your API key:
- API keys stored in .env files (not tracked by Git)
- No hardcoded secrets in source code
- .gitignore prevents accidental key exposure

## 🛠️ Troubleshooting

*Common Issues:*
1. *API Key Error*: Ensure key starts with 'AIza' and is from Google AI Studio
2. *Model Not Found*: Run test_simple_request() to find working models
3. *500 Errors*: Usually temporary - try different model or restart

*Getting Help:*
- Run fix_common_issues() for guided troubleshooting
- Check that your API key is from Google AI Studio (not Google Cloud)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Test with your own API key
4. Submit a pull request

## 📄 License

MIT License - feel free to use and modify!

## ⚠️ Disclaimer

Educational project. Keep API keys secure and monitor usage to avoid unexpected charges.

---

*Made with ❤️ using Google's Gemini AI*
