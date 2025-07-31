# 📚 Book Recommendation Chatbot using IBM Watson Assistant

## 🔍 Overview

This project is a **Book Recommendation Chatbot** designed using **IBM Watson Assistant**. The chatbot interacts with users through a conversational interface and provides book suggestions based on genres, age groups, interests, and other user preferences.

## 🚀 Features

- 📖 Recommends books across various genres such as Mystery, Horror, Biographical, Children’s Books, etc.
- 💬 Understands natural language queries and responds in a human-like manner.
- 🎯 Personalized recommendations based on user inputs.
- 👋 Handles greetings, small talk, and queries about different types of books.
- 🧠 Built on IBM Watson Assistant's NLP capabilities for training intents and dialog flows.

## 🧩 Technologies Used

- **IBM Watson Assistant** – For creating and managing intents, entities, and dialog.
- **Node.js / Python / Webhooks (Optional)** – For backend integration or extended functionality.
- **JSON / CSV** – For managing intents and entities data.
- **IBM Cloud** – Hosting Watson Assistant and related services.

## 📁 Project Structure

```
📦book-recommendation-chatbot
 ┣ 📂intents
 ┃ ┗ intents.csv
 ┣ 📂entities
 ┃ ┗ genres.csv
 ┣ 📂dialog
 ┃ ┗ dialog-flow.json
 ┣ 📂webhook (Optional)
 ┃ ┗ server.js / server.py
 ┣ README.md
 ┗ chatbot-config.json
```

## 🛠️ How to Set Up

1. **Create a Watson Assistant Instance** on [IBM Cloud](https://cloud.ibm.com/catalog/services/watson-assistant).
2. **Import Intents and Entities** from CSV files into Watson Assistant.
3. **Build Dialog** by using pre-defined dialog-flow or customizing your own.
4. (Optional) **Integrate Backend Webhook** if you want to fetch live data or external APIs.
5. Deploy chatbot to your website, app, or messaging platform (e.g., Slack, Messenger).

## 💡 Sample Intents

- `greet`: Hello, hi, good morning...
- `recommend_books`: Can you suggest me a book? I want a mystery novel...
- `book_genre`: What kind of books do you have? Recommend genres...
- `goodbye`: Bye, See you, Exit...

## 📚 Sample Genres

- Horror  
- Mystery  
- Biography  
- Fantasy  
- Children  
- Self-help  
- Science Fiction  
- Historical

## 🗣️ Example Conversation

**User:** Hi there!  
**Bot:** Hello! Ready to dive into a good book? What genre are you interested in?  

**User:** Recommend me a horror story.  
**Bot:** Sure! You might enjoy _"The Haunting of Hill House"_ by Shirley Jackson.

## 📌 Future Enhancements

- Integrate real-time book data from public APIs (e.g., Google Books API).
- Add user profile memory for better personalization.
- Enable multilingual support.
- Deploy on messaging platforms like WhatsApp or Telegram.

## 🤝 Contributions

Contributions, suggestions, or improvements are welcome! Feel free to fork the repo and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
