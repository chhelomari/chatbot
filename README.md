# Chatbot Project

## Description
This project involves the creation and deployment of a chatbot for answering visitors' questions on a website. The chatbot is designed to understand and respond in English and is built using the DialoGPT-small model from Hugging Face.
I am downloading two models, the first one is where the chatbot gives you options of the things you might want to know about the website, when you click on any option, it generates the answer for you, the second one is where you click on any option, it directly takes you to the specific page according to the option." 

## Features
- Responds to basic and predefined questions.
- Can answer specific questions related to the Technologica website.
- Provides flexible responses to slightly varied questions.
- GUI with dark blue and grey color scheme.
- Options-based interaction for ease of use.

## Technologies Used
- Python
- Flask
- JavaScript
- HTML/CSS
- Hugging Face Transformers
- DialoGPT-small-french model

## Installation

### Prerequisites
- Python 3.7 or higher
- Virtual environment setup
- Required Python packages (listed in `requirements.txt`)

### Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/chatbot.git
    cd chatbot
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the necessary model files from Hugging Face:
    - `model.safetensors`
    - `config.json`
    - `vocab.json`
    - `merges.txt`

    Place these files in the appropriate directory (e.g., `models/`).

### Running the Application
1. Run the Flask application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://localhost:5000` to interact with the chatbot.

## Project Structure
chatbot/
│
├── chatbot/
│ ├── init.py
│ ├── chatbot.py
│ ├── templates/
│ │ └── index.html
│ ├── static/
│ │ ├── styles.css
│ │ └── script.js
│ └── models/
│ ├── model.safetensors
│ ├── config.json
│ ├── vocab.json
│ ├── merges.txt
│
├── app.py
├── requirements.txt
└── README.md


## Usage
- The chatbot will respond to basic greetings and questions about Technologica.
- Users can interact with the chatbot through the web interface.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or suggestions, please contact [chelsealeague2012@gmail.com].

