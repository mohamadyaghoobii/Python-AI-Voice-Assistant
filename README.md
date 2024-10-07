Python AI Voice Assistant
This is a Python-based AI Voice Assistant that integrates with OpenAI's powerful language models and LiveKit for real-time audio processing. The assistant can handle voice inputs, process queries using AI, and deliver spoken responses.

Features
Real-time voice input and output.
Powered by OpenAI's language models for intelligent responses.
Integrated with LiveKit for low-latency audio streaming and communication.
Easily customizable for various tasks or personal assistants.
Prerequisites
Before running the project, you need to set up the following:

LiveKit: LiveKit is a real-time audio and video communication platform that enables seamless, low-latency streaming. In this project, it is used to handle voice inputs and outputs efficiently.

Learn more: LiveKit Documentation
OpenAI API: OpenAI's API is used to process natural language queries and generate AI-driven responses.

Installation
1:Clone the repository:
git clone https://github.com/mohamadyaghoobii/python-ai-voice-assistant.git
cd python-ai-voice-assistant

2:Install the required dependencies:
pip3 install -r requirements.txt

 
3:Set up your environment variables. Rename the .env.example file to .env and provide the required values:
LIVEKIT_URL=""
LIVEKIT_API_SECRET=""
LIVEKIT_API_KEY=""
OPENAI_API_KEY=""

These environment variables are needed for connecting to LiveKit for real-time audio communication and OpenAI for AI responses.
