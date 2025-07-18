# 04. 🧭 Creating Your Own Conversational Flow with Watson Assistant
## 💻 BUS 118I Digital Innovation

---

## 🎯 Learning Goal: 
- Understand the purpose of intents
- Understand how to create your own dialog or conversational flow

---

## ⏱️ Estimated time: 
- 45 minutes

---

## 📚 Additional resources:

- [03. Using Chatbots to Conduct Interviews](https://docs.google.com/document/d/1-b-n7r9vf1DmEZ9_AuSV2Y3QRRlZKSRwe-RaMKN36ro/edit?usp=sharing) (Last week’s Tech assignment)
- [Creating Intents](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-intents)
- [Dialog Overview](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-build)
- [Building a conversational flow:](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview)
    - [Special conditions](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-special-conditions)
    - [Configuring the jump to action](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-jump-to-config)
    - [Conditional responses](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-multiple)

---

## 🔽 Steps:

1. Review lecture to get a better understanding of **intents**

2. Review lecture to get an idea of how to create your own dialog

3. For this conversational flow in **Step 4** to work, you should have a solid understanding of [special conditions](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-special-conditions) (specifically using "true"), defining [what the chatbot should do next](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-jump-to-config), and [conditional responses (if statements)](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview#dialog-overview-multiple). These concepts can be found in the ["Creating a dialogue"](https://cloud.ibm.com/docs/watson-assistant?topic=watson-assistant-dialog-overview) document. **!!Please read the mentioned sections in the document before getting started!!**

4. After reading the IBM documentation, you will create your own chatbot interviewer. **Please create your own assistant with the following questions in order:**

- What's your favorite movie genre (e.g.,action, comedy, or sci-fi)
- Normally, where do you watch movies?
- Where do you find out about new movies coming out?
- Have you heard of the new movie "Avengers: End Game"?
   - If the answer is positive (yes), ask: “What do you know about it?”
   - If the answer is negative (no), ask “Which new movie are you looking forward to seeing?”
  
   
5. After each question, please **add a general acknowledgment message** before moving onto the next question:
- For example, the statement highlighted in blue is a general acknowledgement message: 
    - **Chatbot:** Could you introduce yourself in 2-3 sentences, especially your top talents?
    - **User:** I’m a student at San Jose State University and am currently studying management information systems. I’m really interested in learning more about AI.
    - **Chatbot:** Thank you for sharing about yourself!
    - **Chatbot:** What's your favorite movie genre (e.g.,action, comedy, or sci-fi)?

---


## 📝 Deliverables

**Please submit a pdf document with**
2-3 screenshots of the preview of your conversational chatbot. Please interact with your chatbot before taking screenshots.


---

## 🎉 Congratulations on completing this lab! You've taken another important step in mastering AI-powered conversational design.


