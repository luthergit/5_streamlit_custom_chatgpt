# Your Custom ChatGPT 🚵‍♀️

This application utilizes Streamlit to create a custom chat interface with a GPT-based language model. Users can interact with the chatbot by sending messages, and the bot responds accordingly using the OpenAI GPT-3.5-turbo model.


## Usage

1. Enter a system role and send a message in the provided text inputs.
2. The system role can be used to simulate system messages in the chat.
3. The chatbot responds to user messages using the GPT-3.5-turbo model.
4. Messages sent by the user and the chatbot are displayed in the chat interface alternately.

## Functionality

- `ChatOpenAI`: Initializes the GPT-based language model for chat interactions.
- `SystemMessage`, `HumanMessage`, `AIMessage`: Classes representing system, human, and AI messages respectively.
- The application stores messages in the session state and updates the chat interface accordingly.

## Dependencies

- Streamlit
- Langchain
- OpenAI
- Python dotenv
