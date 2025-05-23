# LangChain Chatbot with OpenAI

A simple yet powerful chatbot application built using LangChain and OpenAI's GPT-3.5 Turbo model. This project demonstrates the integration of LangChain with OpenAI's API to create an interactive chat interface using Streamlit.

## 🚀 Features

- Interactive chat interface using Streamlit
- Powered by OpenAI's GPT-3.5 Turbo model
- LangChain integration for enhanced prompt management
- Environment variable support for secure API key management
- LangSmith tracing support for monitoring and debugging

## 📋 Prerequisites

- Python 3.8 or higher
- OpenAI API key
- LangChain API key (optional, for LangSmith tracing)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory with your API keys:
```
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
```

## 🚀 Usage

1. Run the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the URL shown in the terminal (typically http://localhost:8501)

3. Enter your questions in the text input field and get responses from the AI assistant

## 🔧 Configuration

The application uses the following environment variables:
- `OPENAI_API_KEY`: Your OpenAI API key
- `LANGCHAIN_API_KEY`: Your LangChain API key (optional)
- `LANGCHAIN_TRACING_V2`: Set to "true" for LangSmith tracing

## 📝 Project Structure

```
├── app.py              # Main application file
├── requirements.txt    # Project dependencies
├── .env               # Environment variables (not tracked in git)
└── README.md          # Project documentation
```

## 🔒 Security

- Never commit your `.env` file to version control
- Keep your API keys secure and don't share them publicly

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- OpenAI for providing the GPT-3.5 Turbo model
- LangChain for the amazing framework
- Streamlit for the web interface 