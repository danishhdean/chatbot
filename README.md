#University FAQ Chatbot

📝 Overview
This project implements a rule-based University FAQ Chatbot using Python and the spaCy NLP library. It’s designed to answer frequently asked questions about university life 🎒—like admissions, courses, fees, and library services—by recognizing user intent and responding with helpful guidance 💬.


✨ Features
🧠 Natural Language Processing: Utilizes spaCy to tokenize, lemmatize, and clean up user input.

🎯 Intent Recognition: Matches queries to predefined intents (like "admission" or "fees") using keyword rules.

💻 Interactive Interface: Simple command-line experience for real-time chatting.

🛠️ Extensible FAQ System: Easily customizable intent-response structure for scaling across more topics.


💬 Interact with the Chatbot
Type a question like:

"What are the admission requirements?"

"Library timings?" …and get an immediate response!

Type 'exit' to end the session gracefully 👋

🧪 Example Interaction
University FAQ Chatbot
Type 'exit' to end the chat.

You: Hello  
Chatbot: Hello! How can I assist you today? 😊  
You: What are the fees?  
Chatbot: The fee structure varies by program. Check the 'Fees and Payments' page on our website. 💰  
You: exit  
Chatbot: Goodbye! Have a great day! 🌟
🧩 Project Structure
🔍 How It Works
🧹 Preprocessing: preprocess_text uses spaCy to clean and prepare user input.

🧠 Intent Matching: match_intent_rule_based detects the closest intent from the input.

📤 Response Generation: The chatbot picks a relevant answer from the faq_responses dictionary.

🔁 Chat Loop: The program keeps running until you type 'exit'.

⚠️ Limitations
❗ Rule-based only: might not handle complex or vague questions.

🔑 Relies on fixed keywords, so phrasing matters!

🧠 No memory of past conversation or context awareness.

🚀 Future Improvements
🧬 Add machine learning for smarter intent classification.

🧠 Context tracking for multi-turn conversations.

🌐 Create a sleek web interface for broader accessibility.

📚 Expand the FAQ scope to more departments and scenarios.
