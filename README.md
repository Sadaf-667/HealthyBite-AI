# HealthyBite AI

**An AI-powered chatbot for food, nutrition, and healthy eating information.**

HealthyBite AI is a simple conversational chatbot developed using Python, Streamlit, and the Groq API. It allows users to ask questions related to healthy eating, fruits, vegetables, nutrition, affordable meals, and healthy recipes.

The application uses the `openai/gpt-oss-120b` model through the Groq API to generate responses. A keyword-based filtering mechanism is also implemented to restrict conversations to food and nutrition-related topics.

## Features

- AI-generated responses to food and nutrition-related questions.
- Information about healthy eating, fruits, vegetables, vitamins, proteins, and calories.
- Guidance on affordable meals, ingredients, and cooking.
- Assistance with healthy recipe-related questions.
- Keyword-based topic filtering to restrict unrelated queries.
- Session-based conversation history using Streamlit session state.
- Environment variable configuration for API key management.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Chat interface |
| Groq API | AI response generation |
| GPT-OSS 120B | Language model |
| python-dotenv | Loading environment variables |

## How It Works

1. The user enters a question through the Streamlit chat interface.
2. The application checks the question against a predefined list of food-related keywords.
3. If the question passes the keyword check, it is sent to the Groq API.
4. The AI model generates a response using the system instructions and conversation history.
5. The generated response is displayed in the chat interface.

Questions that do not match the predefined keywords receive a message explaining that the chatbot only handles food, nutrition, and healthy eating topics.

## Future Improvements

- Improve keyword-based topic detection.
- Expand the list of supported nutrition-related topics.
- Improve handling of follow-up questions.
- Add more detailed food and nutrition reference information.
- Introduce additional chatbot features.

## Disclaimer

HealthyBite AI provides general information about food, nutrition, and healthy eating. Its responses are AI-generated and should not replace professional medical or dietary advice.

## Author

Developed as an academic project using Python, Streamlit, and the Groq API.