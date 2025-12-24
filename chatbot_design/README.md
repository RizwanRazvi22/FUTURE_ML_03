# Chatbot Design

This folder documents the **design and conversation structure** of the Customer Support Chatbot developed for  
**Machine Learning Internship – Task 3**.

The focus here is on how the chatbot understands user queries and responds using intent-based conversation design in Dialogflow.

---

## 🧠 Design Approach

The chatbot follows an **intent-driven architecture**, where each user query is mapped to a predefined intent.

The design ensures:
- Simple and natural conversations
- Fast responses to common customer queries
- Graceful handling of unknown inputs
- Easy extensibility for future features

---

## 🗂 Intent Structure

The chatbot is built using the following core intents:

### 1️⃣ Greeting Intent
- Handles greetings such as *Hi*, *Hello*, and *Hey*
- Provides a friendly welcome message to users

### 2️⃣ Order Status Intent
- Handles questions like *Where is my order?*
- Guides users to track their order status

### 3️⃣ Refund & Cancellation Intent
- Manages refund and cancellation-related queries
- Provides clear next steps for customers

### 4️⃣ Default Fallback Intent
- Handles unrecognized or unclear queries
- Responds politely and redirects users to supported topics

---

## 🔄 Conversation Flow

1. User initiates the conversation
2. Greeting intent is triggered
3. User asks a support-related question
4. Relevant intent processes the query
5. Chatbot responds with a predefined answer
6. Fallback intent handles unsupported queries

---

## 🎯 Design Goals

- Improve customer experience through automation
- Reduce repetitive customer support workload
- Maintain clarity, politeness, and accuracy in responses

---

This design documentation works alongside the screenshots and project documentation to provide a complete overview of the chatbot’s structure and logic.
