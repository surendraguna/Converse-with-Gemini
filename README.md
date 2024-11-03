# Converse with Gemini

## Description
**Converse with Gemini** is an interactive AI-driven application that enables users to engage in conversations with an AI powered by the Gemini AI Studio API. Built with a Spring Boot backend and a simple HTML, CSS, and JavaScript frontend, the app offers a user-friendly interface to input questions or prompts and receive AI-generated responses. This project demonstrates how to integrate a conversational AI API in a clean and accessible UI, making it useful for developers interested in AI, chatbot applications, or conversational UX design.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)

## Installation
Follow these steps to set up the **Converse with Gemini** project locally:

### Clone the Repository
  ```bash
  git clone https://github.com/surendraguna/converse-with-gemini.git
  ```
### Set Up the Backend (Spring Boot):

1. **Open the project in Visual Studio Code**:
   - Open VS Code and go to `File` > `Open Folder...`, then select the project folder (`converse-with-gemini`).

2. **Make sure you have Java and Maven installed** on your machine.

3. **Install the following VS Code extensions** if you haven't already:
   - Java Extension Pack
   - Spring Boot Extension Pack
4. **Add your Gemini AI Studio API key in** `src/main/resources/application.properties`:
     ```bash
     gemini.api.key=YOUR_API_KEY
     ```
### Run the Application:
1. In the terminal, navigate to the project’s root directory.
2. Use Maven to run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```
### Access the Applicaiton:
- Open your browser and got to `http:/localhost:8080` to see the UI.

## Usage

1. Open the application in a web browser.
2. Type a question or prompt into the input field.
3. Click **Submit** to send your prompt to the AI.
4. The AI response will appear below the input field.

### Example:
  ```bash
    User Prompt: "Tell me about the solar system."
    AI Response: "The solar system consists of the Sun and the objects that orbit it..."
  ```

## Features

- **Real-time AI Responses**: Send prompts and get responses from the Gemini AI.
- **Simple UI**: User-friendly interface built with HTML, CSS, and JavaScript.
- **Spring Boot Backend**: Efficient and secure communication between the frontend and AI API.
- **Gemini AI Integration**: Uses the Gemini AI Studio API for conversational AI capabilities.

## Contributing
Contributions are welcome! Follow these steps if you wish to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request for review.


