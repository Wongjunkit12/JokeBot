# Make Me Laugh - An AI Powered JokeBot for Mental Health

A web application that leverages fine-tuned GPT-3.5-Turbo to generate contextually appropriate humor as a therapeutic tool for mental health support.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

HumorHealth is a Final Year Project that addresses the growing global mental health crisis by providing an accessible, light-hearted approach to emotional support. The application uses a fine-tuned version of GPT-3.5-Turbo to generate contextually appropriate humor based on user input, offering a free alternative to traditional therapeutic methods.

### The Problem
- 792 million people worldwide struggle with mental disorders
- 264 million people specifically battle depression
- Traditional therapeutic solutions can be expensive and inaccessible
- Existing AI humor generators lack contextual understanding and emotional intelligence

### Our Solution
We've developed a web application that combines the therapeutic benefits of humor with advanced AI technology to provide:
- Personalized joke generation based on user keywords
- Voice recognition for hands-free interaction
- A user-friendly interface built with Gradio
- Enhanced contextual understanding through model fine-tuning

## Features
- Keyword-based joke generation
- Voice input support
- Fine-tuned GPT-3.5-Turbo model for better humor quality
- Web-based interface accessible from any device
- Real-time response generation

## Technology Stack
- **Backend**: Python 3.10
- **Frontend**: Gradio 3.41.0
- **AI Model**: OpenAI GPT-3.5-Turbo
- **Data Processing**: Pandas, Beautiful Soup 4
- **Voice Recognition**: Speech Recognition 3.10.0
- **Web Automation**: Selenium 4.9
- **Development Tools**: VS Code, Pylint

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Wongjunkit12/JokeBot.git
cd jokebot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key:
```bash
export OPENAI_API_KEY='your-api-key-here'  # On Windows: set OPENAI_API_KEY=your-api-key-here
```

## Usage

1. Start the application:
```bash
python WorkingGradio.py
```

2. Open your web browser and navigate to the local address shown in the terminal (typically http://127.0.0.1:7860)

3. Enter keywords or use voice input to generate humor content

## Project Structure
```
humorhealth/
├── app.py              # Main application file
├── model/
│   ├── fine_tuning.py  # Model fine-tuning scripts
│   └── inference.py    # Inference handling
├── data/
│   ├── raw/           # Raw joke dataset
│   └── processed/     # Processed training data
├── utils/
│   ├── preprocessing.py
│   └── voice.py       # Voice recognition utilities
├── tests/             # Unit tests
└── requirements.txt   # Project dependencies
```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
