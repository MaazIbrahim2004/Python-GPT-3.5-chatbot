# Python-GPT-3.5-chatbot

A simple Python chatbot using OpenAI's GPT-3.5-turbo.

## Setup

### Prerequisites
- Python 3.x
- `openai` Python package

### Installation
1. Clone this repository:
   ```
   git clone https://github.com/your_username/Python-GPT-Chatbot.git
   ```

2. Navigate to the project directory:
   ```
   cd Python-GPT-Chatbot
   ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

### API Key Configuration

To run the chatbot, you'll need to set your OpenAI API key. 

#### Using Environment Variables (Recommended)
1. Set an environment variable named `OPENAI_API_KEY` with your OpenAI API key value:
   ```
   export OPENAI_API_KEY='your_api_key_here'
   ```

2. Run the script. The script will automatically fetch the API key from the environment variable.

#### Local Configuration (Alternative)
1. Create a `config.py` file in the project directory with the content:
   ```python
   API_KEY = "your_api_key_here"
   ```

2. Make sure to add `config.py` to your `.gitignore` file to avoid accidentally pushing it to GitHub.

3. Run the script. The script will fetch the API key from the `config.py` file.

## Running the Chatbot

To start the chatbot, simply run:

```
python main.py
```

Enter your questions or statements, and the chatbot will respond. Type "quit" or "exit" to end the session.

