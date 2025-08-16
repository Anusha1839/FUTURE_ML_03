# FUTURE_ML_03
# Customer Support Chatbot
A machine learning-powered chatbot built with Dialogflow and a custom HTML/CSS/JavaScript front-end to provide instant customer support. This project demonstrates skills in conversational AI, intent design, and API integration.

# 🚀 Features
- Natural Language Understanding: Capable of understanding a wide range of customer questions and phrases.

- Intent-Based Conversation: Navigates conversation flows for different support categories, including technical and delivery issues.

- Entity Recognition: Identifies key information like product names and specific problems directly from user input.

- Dynamic UI: Displays interactive buttons and custom responses based on the chatbot's logic.

- API Integration: Connects a static HTML front-end to a powerful Dialogflow agent via a secure API.

# 🛠️ Technologies Used
- Frontend
  
HTML5: For the page structure and chatbot container.

CSS3: For styling and visual effects (e.g., gradients, borders, shadows).

JavaScript: To handle user interactions and manage the connection to the Dialogflow API.

- Backend/AI
  
Dialogflow (Google): The primary no-code platform used to design the conversational flow, intents, and entities.

Google Cloud: The underlying service hosting the Dialogflow agent.

# 🧠 Chatbot Logic & Design
- The chatbot is designed around a clear and efficient conversational flow:

+ Default Welcome Intent: Greets the user and presents options for "Technical Problem" or "Delivery Problem" as buttons.

+ DeliveryProblem_AskNumber: Prompts the user for their order number if they don't provide it in their initial query.

+ DeliveryProblem_WithNumber: Handles delivery inquiries that include an order number, confirming the status.

+ TechnicalProblem: A top-level intent that serves as a general entry point for technical issues.

+ TechnicalProblem - Specific: A follow-up intent that uses entities to identify both the @product and the @problem (e.g., "My iPhone has a screen issue").

+ Thank You: A graceful exit from the conversation.

- Entities
    -> @product: Recognizes various products like smartphone, tv, computer, and laptop, including synonyms (e.g., iPhone, Samsung).

    -> @problem: Identifies specific issues such as screen issue, battery issue, no power, and camera issue, with a list of synonyms for each.

#⚙️ How to Run the Project
Open the project folder:

cd [Your Project Folder Name]

Set up your Dialogflow Agent

Create a new Dialogflow agent in the Dialogflow Console.

Replicate the intents and entities as described in the "Chatbot Logic & Design" section.

Find your Project ID by clicking the gear icon (⚙️) next to your agent's name.

Edit the index.html file

Open your browser and navigate to the local address provided (e.g., http://localhost:8080).

#📞 Contact
LinkedIn:  https://www.linkedin.com/in/dhanusha-katakam-ediga-3756ab341/

#futureInterns
