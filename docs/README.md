# Documentation

This folder contains supporting documentation for **Machine Learning Internship – Task 3**, which focuses on building a **Customer Support Chatbot** using Dialogflow.

The documents here describe the chatbot’s design approach, intent structure, and conversational flow.

---

## 📌 Chatbot Design Overview

The chatbot is designed to handle common customer support queries in a structured and user-friendly manner.  
It uses **intent-based conversation handling** to understand user input and provide accurate responses.

Key design goals:
- Provide quick and clear responses to user queries
- Handle greetings and basic interactions politely
- Support order tracking and refund-related questions
- Gracefully handle unknown or unclear inputs

---

## 🧠 Intents Implemented

The chatbot includes the following core intents:

- **Greeting Intent**  
  Handles user greetings such as *Hi*, *Hello*, and *Hey*.

- **Order Status Intent**  
  Responds to queries related to order tracking and delivery status.

- **Refund & Cancellation Intent**  
  Manages customer requests for refunds and order cancellations.

- **Default Fallback Intent**  
  Handles unrecognized user inputs and guides users back to supported queries.

---

## 🔄 Conversation Flow

1. User starts with a greeting  
2. Chatbot responds and waits for a query  
3. User asks about orders or refunds  
4. Relevant intent is triggered  
5. Chatbot provides a predefined response  
6. Unknown queries are handled using fallback responses

---

## 🛠 Tools Used

- Dialogflow (No-Code / Low-Code Chatbot Builder)
- Google Cloud Platform
- Intent-based NLP

---

This documentation complements the screenshots provided in the `screenshots/` folder and helps reviewers understand the chatbot’s internal structure and logic.
