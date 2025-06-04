# ChatBot 2025: Full-Stack Development Workshop

Welcome to the **ChatBot 2025** project, part of the *Chatbot Development Workshop V01* by Worachat Wannawong, Ph.D., 2025. This repository contains the full-stack implementation of a simple chatbot, with a back-end built using Python and NLTK (Natural Language Toolkit) and a front-end designed with HTML, CSS, and JavaScript for a modern, user-friendly interface. The project is designed for educational purposes, demonstrating chatbot development and deployment.

## Project Overview

- **Back End**: A Python-based chatbot using NLTK for pattern matching and pronoun reflection, optimized for Google Colab.
- **Front End**: A web-based chat interface with a clean, modern UI, deployable via static hosting.
- **UI Design**: A mockup created in Canva to guide the front-end aesthetic.
- **Deployment**: Hosted on [Tiiny Host](https://tiiny.host/) for easy static site publishing.

**Live Demo**: [https://worachat-w-chatbot-2025.tiiny.site/](https://worachat-w-chatbot-2025.tiiny.site/)

## Back End Development

### Overview
The back-end is implemented in Python using the NLTK library to create a simple chatbot capable of handling basic conversational patterns. It runs in a Google Colab environment, making it accessible for workshop participants to experiment with and extend.

### Files
- **NLTK_Chatbot_Development_Workshop_Training_BED_V01.ipynb**: Jupyter Notebook containing the back-end code.

### Setup
1. **Environment**: Open the notebook in [Google Colab](https://colab.research.google.com/).
2. **Dependencies**: The notebook uses the `nltk` library. Install it in Colab if needed:
   ```python
   !pip install nltk
   ```
3. **Execution**:
   - Run the notebook cells to initialize the chatbot.
   - The code defines conversation patterns and uses NLTK's `Chat` utility for pattern matching and pronoun reflection.
   - A custom `chat_loop()` function enables interactive input/output in Colab.
4. **Usage**:
   - Enter phrases like "hi", "how are you?", or "I am Worachat" to interact with the chatbot.
   - Type "quit" to exit the conversation.

### Key Features
- **Pattern Matching**: Uses regular expressions for flexible input handling (e.g., `hello|hi|hey`).
- **Reflections**: Swaps pronouns (e.g., "I am" to "you are") for dynamic responses.
- **Extensibility**: Easily add new patterns and responses to the `pairs` list.

## Front End Development

### Overview
The front-end is a static web application built with HTML, CSS, and JavaScript, replicating the back-end chatbot's functionality in a browser-based interface. The UI is designed to be modern, minimalist, and user-friendly, inspired by the Canva mockup.

### Files
- **NLTK-Chatbot-Development-Workshop-Training-FED-V01.html**: HTML file containing the front-end code, including CSS for styling and JavaScript for chatbot logic.

### Setup
1. **Local Development**:
   - Open `NLTK-Chatbot-Development-Workshop-Training-FED-V01.html` in a web browser to test locally.
   - No additional dependencies are required, as it uses vanilla JavaScript and inline CSS.
2. **UI Design Reference**:
   - The UI is based on a mockup created in Canva: [https://yogurt.my.canva.site/00-nltk-chatbot-development-workshop-training-fed](https://yogurt.my.canva.site/00-nltk-chatbot-development-workshop-training-fed).
   - Features include:
     - Clean chat bubbles (user: right-aligned, bot: left-aligned).
     - A sleek text input field with a vibrant "Send" button.
     - A modern color palette (blues, grays, white) with a subtle digital pattern background.
3. **Customization**:
   - Modify the CSS in the `<style>` section to adjust colors, fonts, or layout.
   - Update the JavaScript `pairs` array to add new conversation patterns or responses.

### Key Features
- **Interactive Chat**: Users can type messages and receive bot responses in real-time.
- **Reflections**: JavaScript replicates NLTK's pronoun-swapping logic.
- **Responsive Design**: The UI adapts to various screen sizes for accessibility.

## Deployment

### Hosting on Tiiny Host
The front-end is deployed using [Tiiny Host](https://tiiny.host/), a platform for hosting static websites.

1. **Steps**:
   - Create a zip file containing `NLTK-Chatbot-Development-Workshop-Training-FED-V01.html`.
   - Visit [https://tiiny.host/manage/upload](https://tiiny.host/manage/upload).
   - Upload the zip file to publish the site instantly.
2. **Live URL**: [https://worachat-w-chatbot-2025.tiiny.site/](https://worachat-w-chatbot-2025.tiiny.site/)
3. **Management**: Use [https://tiiny.host/manage](https://tiiny.host/manage) to update or manage the hosted site.

### Notes
- Tiiny Host is ideal for static assets, making it perfect for the front-end HTML file.
- The back-end (Python/NLTK) remains in Colab and is not hosted, as it requires a runtime environment.

## Full-Stack Integration
While the back-end and front-end are separate in this workshop, they share the same conversational logic:
- **Back End**: Handles processing in a Python environment, ideal for learning NLTK and testing logic.
- **Front End**: Translates the same patterns and reflections into JavaScript for a browser-based experience.
- **Future Integration**: To create a true full-stack application, consider hosting the Python back-end on a server (e.g., Flask or FastAPI) and connecting it to the front-end via an API. This is beyond the scope of the workshop but can be explored for advanced projects.

## Getting Started
1. **Back End**:
   - Open `NLTK_Chatbot_Development_Workshop_Training_BED_V01.ipynb` in Google Colab.
   - Run the cells to start the chatbot and experiment with inputs.
2. **Front End**:
   - Open `NLTK-Chatbot-Development-Workshop-Training-FED-V01.html` in a browser or deploy it via Tiiny Host.
   - Interact with the chatbot through the web interface.
3. **UI Design**:
   - Reference the Canva mockup for design inspiration: [https://yogurt.my.canva.site/00-nltk-chatbot-development-workshop-training-fed](https://yogurt.my.canva.site/00-nltk-chatbot-development-workshop-training-fed).
4. **Deployment**:
   - Follow the Tiiny Host instructions to publish the front-end.

## Contributing
- **Back End**: Add new patterns to the `pairs` list in the notebook to expand the chatbot's capabilities.
- **Front End**: Enhance the UI by modifying CSS or adding animations in JavaScript.
- **Feedback**: Submit issues or suggestions to improve the workshop materials.

## Credits
- **Instructor**: Worachat Wannawong, Ph.D.
- **Year**: 2025
- **Tools**: Python, NLTK, HTML, CSS, JavaScript, Google Colab, Tiiny Host, Canva

## License
This project is for educational purposes and may be freely used or modified for non-commercial workshop activities.
