## 🚀 Getting Started

1. **Set up your environment**:
   ```bash
   # Make sure you have your OpenAI API key
   # Get your API key from: https://platform.openai.com/api-keys
   ```

2. **Install OpenAI Agents SDK**:
   ```bash
   pip install openai-agents
   ```

3. **Install dependencies**:
   ```bash
   # Install required packages
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
  
   
   # Edit .env and add your OpenAI API key
   # OPENAI_API_KEY=sk-your_openai_key_here


4. **Test the agent**:
   ```bash
   # Run the agent directly
   python agent.py
   
   # Or run the Streamlit web interface
   streamlit run app.py
   ```

6. **Try different execution methods**:
   - Test synchronous execution: "What's the weather like today?"
   - Test asynchronous execution: "Tell me a story about AI"
   - Test streaming responses: "Explain machine learning in detail"

## 🧪 Sample Prompts to Try

- **General Questions**: "What's the capital of France?"
- **Creative Tasks**: "Write a short poem about technology"
- **Problem Solving**: "How can I improve my productivity?"
- **Explanations**: "Explain quantum computing in simple terms"



## 💡 Pro Tips

- **Start Simple**: Begin with basic functionality and add complexity gradually
- **Test Often**: Try different prompts to understand agent behavior
- **Read Instructions**: Clear instructions lead to better agent behavior
- **Experiment**: Try different execution methods to see the differences

## 🚨 Troubleshooting

- **API Key Issues**: Make sure your `.env` file contains a valid `OPENAI_API_KEY`
- **Import Errors**: Ensure all dependencies are installed with `pip install -r requirements.txt`
- **Rate Limits**: If you hit rate limits, wait a moment before trying again