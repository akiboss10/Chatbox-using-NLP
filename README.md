# Chatbox-using-NLP
# NLP Chatbox Implementation  

This repository contains the implementation of a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to provide meaningful responses to user inputs by recognizing intents defined in the `intents.json` file. The project utilizes Python, and the chatbot interface is built using **Streamlit**.  
![Screenshot 2024-12-13 153609](https://github.com/user-attachments/assets/7f942355-be19-4b9c-8244-da4779b9924b)

---

## Features  

1. **Intent Recognition:**  
   - Matches user queries with predefined intents and provides appropriate responses.  
   - Uses pattern matching and intent classification techniques.  

2. **Dynamic Responses:**  
   - Returns responses dynamically based on user input and defined patterns.  

3. **Conversation Logging:**  
   - Stores user inputs and chatbot responses in `chat_log.csv` for future analysis.  

4. **Interactive UI:**  
   - Simple, user-friendly interface for interacting with the chatbot.  

5. **Extensibility:**  
   - Can be extended with additional intents, patterns, or APIs for enhanced functionality.  

---

## File Structure  

### **Main Files:**  

1. **`app.py`**  
   - Core Python file to run the chatbot application.  
   - Handles user input, intent recognition, response generation, and logging.  

2. **`intents.json`**  
   - Contains the intent definitions, patterns, and responses.  
   - Example structure:  
     ```json
     {
         "tag": "greeting",
         "patterns": ["Hello", "Hi", "Hey"],
         "responses": ["Hello! How can I help you?", "Hi there! How can I assist you?"]
     }
     ```  

3. **`chat_log.csv`**  
   - Logs all conversations between the user and the chatbot.  
   - Useful for debugging and analyzing user interactions.  

4. **`requirements.txt`**  
   - Contains the list of required Python libraries to run the project.  

5. **`README.md`**  
   - Documentation for the repository.  

---

## Getting Started  

### **Prerequisites**  
To run the chatbot, you need:  
- Python 3.8 or higher  
- Required Python libraries (listed in `requirements.txt`)  

### **Installation Steps**  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/nlp-chatbox.git
   cd nlp-chatbox
