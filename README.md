# ConversationalAI

## Overview

This project implements a voice-enabled conversational AI system powered by Azure Cognitive Services and OpenAI APIs. The system supports seamless spoken interactions, combining speech-to-text, intelligent response generation, and text-to-speech capabilities.

---

## Getting Started

### Prerequisites

#### Azure Cognitive Services
Ensure you have an active **Azure Cognitive Services Speech** resource to obtain the required API key and region information.

#### OpenAI API Key
Sign up for OpenAI and generate an API key to enable the LLM's functionality.

---

### Configuration

#### `.env` File
Create a `.env` file in the root directory of the project with the following keys:

```plaintext
SPEECH_KEY=YourCognitiveServiceSpeechAPIKey
SPEECH_REGION=YourCognitiveServiceRegion
SPEECH_LANGUAGE=YourLanguage
OPENAI_KEY=YourOpenAIKey
```

Replace the placeholders with your actual API keys and preferred language settings.

---

### Installation

Install the required Python libraries to run the project:

```bash
pip install azure-cognitiveservices-speech
pip install python-dotenv
pip install openai
pip install simpleaudio
```

These libraries facilitate speech recognition, environment configuration, interaction with the OpenAI API, and audio playback.

---

### Ready to Use
Once configured and dependencies are installed, you can start interacting with the conversational AI system. For more details on execution and usage, check the project scripts and documentation.