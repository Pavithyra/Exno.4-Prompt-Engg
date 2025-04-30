# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 30.04.2025                                                                           
### REGISTER NUMBER : 212222060174
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  
**1. Direct Instruction Prompts**
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
**2. Contextual Prompting**
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
**3. Persona-Based Prompting**
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
**4. Few-Shot Prompting**
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
**5. Chain of Thought Prompting**
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
**6. Instruction with Constraints**
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
**7. Reflective Prompting**
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
**8. Tabular Format Prompting**
Objective: Help the chatbot present structured options clearly, enabling customers to select a service efficiently.
Prompt Pattern:
Prompt:
"Present the following options in a table when a customer asks for help:
**9. Preceding Question Prompting**
Objective: Enable the chatbot to follow up with relevant questions based on the customer’s initial query.
Prompt Pattern:
Prompt:
"When a customer asks for technical help, follow up with a clarifying question before giving a solution.
Example:
Customer: 'My smartwatch isn't syncing.'
**10. Multi-turn Prompting**
Objective: Allow the chatbot to handle a series of questions in a smooth conversational flow.
Prompt Pattern:
Prompt:
"If a customer starts a conversation about returns and then asks about shipping, maintain the context across turns.
Example:
Customer: 'I want to return my headphones.'
Bot: 'Sure, I can help with that. May I know the reason for the return?'
Customer: 'Also, when will my other order arrive?'
Bot: 'Got it! Let me first process the return, then I’ll check the delivery status of your other order.'"
**11. Emotion-Aware Prompting**
Objective: Detect and respond empathetically to customer emotions such as frustration or confusion.
Prompt Pattern:
Prompt:
"If a customer expresses frustration (e.g., 'I’ve been waiting forever!'), respond empathetically:
'I'm really sorry for the delay — I understand how frustrating that must be. Let me check what’s going on with your order right away.'"
**12. Visual Prompting (for UI-integrated chatbots)**
Objective: Instruct the chatbot to refer to UI elements or visuals when helping users navigate.
Prompt Pattern:
Prompt:
"When a customer asks how to find a feature (e.g., 'Where can I see my invoices?'), refer to visual UI elements:
'You can find your invoices by clicking on the "My Account" section at the top right, then selecting "Billing & Invoices."'"
Result: The various types of Prompts are executed successfully.




# Result: Thus the Prompts were exected succcessfully .

