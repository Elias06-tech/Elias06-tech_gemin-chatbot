# Google Colab Gemini Chatbot

A powerful AI chatbot built with Google's Gemini AI, designed to run in Google Colab with secure API key management.

## Features

- 🤖 Interactive chatbot with conversation memory
- 🎭 Customizable AI personalities
- 📜 Chat history tracking
- 🔧 Multiple chatbot modes (basic and enhanced)
- 🛡️ Secure API key management
- ⚡ Easy setup in Google Colab

## Quick Start

- Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
- Create a new API key
- Copy the API key (starts with 'AIza')


1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook file
3. Run the code - it will guide you through setup


The code will automatically prompt you to enter your API key and create the necessary configuration files.

## Available Functions

### Basic Usage
```python
# Single question
print(ask_gemini("What is machine learning?"))

# Start basic chatbot
run_chatbot()

# Start enhanced chatbot with personalities
run_enhanced_chatbot()
```

### Troubleshooting
```python
# Check API setup
diagnose_api_issue()

# Test models
test_simple_request()

# Check available models
list_available_models()
```

## Chatbot Commands

While chatting, you can use these commands:
- `quit`, `exit`, `bye` - End conversation
- `history` - Show chat history
- `clear` - Clear screen
- `personality [description]` - Set AI personality
- `help` - Show help message

## Security

This project uses environment variables to keep your API key secure:
- API keys are stored in `.env` file (not tracked by Git)
- Never hardcode API keys in source code
- `.gitignore` prevents accidental key exposure

## Requirements

- Google Colab account
- Google AI Studio API key
- Internet connection

## Troubleshooting

### Common Issues:
1. **API Key Errors**: Make sure your key starts with 'AIza'
2. **Model Not Found**: Run `test_simple_request()` to find working models
3. **500 Errors**: Usually temporary, try again or use different model

### Getting Help:
- Run `fix_common_issues()` for guided troubleshooting
- Check that your API key is from Google AI Studio (not Google Cloud)

## Contributing

1. Fork the repository
2. Create your feature branch
3. Make sure to test with your own API key
4. Submit a pull request

## License

MIT License - feel free to use and modify!

## Disclaimer

This project is for educational purposes. Keep your API keys secure and monitor your usage to avoid unexpected charges.
