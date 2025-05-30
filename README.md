# 🎓 Admission ChatBot

A simple, beginner-friendly chatbot built with [Rasa](https://rasa.com/) to assist users with basic admission-related queries. This project serves as an introductory exploration into conversational AI using Rasa's open-source framework.

---

## 🧠 Features

* **Basic Intent Recognition**: Understands simple user intents related to admissions.
* **Predefined Responses**: Provides hardcoded answers to specific questions.
* **Beginner-Friendly Structure**: Organized in a way that's easy to understand for newcomers to Rasa and chatbot development.

---

## 📁 Project Structure

```
.
├── actions/             # Custom action definitions
├── data/                # Training data: NLU, stories, and rules
├── models/              # Trained Rasa models
├── tests/               # Test cases for the chatbot
├── .gitignore           # Git ignore file
├── config.yml           # Rasa pipeline and policies configuration
├── credentials.yml      # Credentials for external services
├── domain.yml           # Domain definition: intents, entities, slots, responses
└── endpoints.yml        # Configuration for action endpoints
```

---

## 🚀 Getting Started

### Prerequisites

* Python 3.7 or higher
* pip (Python package installer)
* [Rasa Open Source](https://rasa.com/docs/rasa/installation/)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Saber0722/Admission_ChatBot.git
   cd Admission_ChatBot
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   *Note: If `requirements.txt` is not present, you can install Rasa directly:*

   ```bash
   pip install rasa
   ```

---

## 🧪 Running the Chatbot

1. **Train the model**

   ```bash
   rasa train
   ```

2. **Start the action server (if custom actions are defined)**

   ```bash
   rasa run actions
   ```

3. **Run the chatbot in the terminal**

   ```bash
   rasa shell
   ```

   *You can now interact with the chatbot directly in your terminal.*

---

## 🛠️ Customization

Feel free to expand the chatbot's capabilities by:

* Adding new intents and training phrases in `data/nlu.yml`.
* Defining new stories in `data/stories.yml` to handle different conversation flows.
* Creating custom actions in the `actions/` directory and updating `domain.yml` accordingly.

---

## 📚 Resources

* [Rasa Documentation](https://rasa.com/docs/)
* [Rasa Tutorials](https://rasa.com/resources/)

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

*This project was created as a learning exercise to explore the basics of chatbot development using Rasa.*

---
