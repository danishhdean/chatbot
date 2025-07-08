# University FAQ Chatbot
Overview
This project implements a rule-based University FAQ Chatbot using Python and the SpaCy library for natural language processing (NLP). The chatbot is designed to answer frequently asked questions about university-related topics such as admissions, courses, fees, library services, and contact information. It uses predefined intents and keyword matching to provide relevant responses to user queries.
Features


Natural Language Processing: Utilizes SpaCy to preprocess user input by tokenizing, lemmatizing, and removing stopwords.
Intent Recognition: Matches user queries to predefined intents (e.g., greeting, admission, fees) using lemmatized keyword-based rules.
Interactive Interface: Provides a command-line interface for users to interact with the chatbot and receive immediate responses.
Extensible FAQ System: Easily customizable dictionary-based FAQ responses and keyword mappings for different intents.


Interact with the chatbot:

Type your question (e.g., "What are the admission requirements?" or "Library timings").
Type exit to end the chat session.


Example interaction:
University FAQ Chatbot
Type 'exit' to end the chat.

You: Hello
Chatbot: Hello! How can I assist you today?
You: What are the fees?
Chatbot: The fee structure varies by program. Check the 'Fees and Payments' page on our website.
You: exit
Chatbot: Goodbye! Have a great day!


Project Structure
How It Works:

Preprocessing: The preprocess_text function processes user input using SpaCy to tokenize, lemmatize, and remove stopwords for cleaner intent matching.
Intent Matching: The match_intent_rule_based function checks for lemmatized keywords in the processed input to identify the user's intent (e.g., "admission" or "fees").
Response Generation: Based on the matched intent, the chatbot selects a response from the faq_responses dictionary.
Chat Loop: The chatbot function runs an interactive loop, accepting user input and providing responses until the user types exit.


Limitations:

The chatbot uses a rule-based approach, which may not handle complex or ambiguous queries effectively.
It relies on predefined keywords, so it may fail to recognize intents if the user input does not contain those keywords.
No support for multi-turn conversations or context retention.


Future Improvements:

Implement machine learning-based intent classification for more robust query handling.
Add context awareness to support follow-up questions.
Integrate a web-based interface for better user experience.
Expand the FAQ database to cover more university-related topics.
