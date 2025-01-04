Burushaski ChatBot Project

Introduction

The Burushaski ChatBot is an AI-based application designed to translate Burushaski phrases into English and provide conversational responses powered by Google Generative AI. This innovative project aims to preserve and promote the Burushaski language by bridging communication gaps and offering user-friendly interaction.

Features

1. Translation

Accurate translations of Burushaski phrases into English using a pre-defined dataset.

Real-time matching of user input to phrases in the dataset.

2. AI-Powered Interaction

Uses Google Generative AI to enhance user experience with contextual and insightful responses.

3. Suggestions

Recommends similar Burushaski phrases for incomplete or incorrect user inputs to improve query accuracy.

4. User Interface

Developed with Streamlit, providing an intuitive and visually appealing platform.

Features customized CSS for enhanced aesthetics.

Technical Overview

1. Core Components

Translation Model

Dataset: Utilizes a Burushaski-to-English phrase dataset.

Functionality: Matches user input to provide accurate translations.

Implementation:

Function: translate_to_english

Searches for exact or partial matches in the dataset and returns translations.

Suggestion System

Functionality: Provides suggestions for similar phrases based on partial matches.

Implementation:

Function: suggest_words

Matches the initial characters of user input with dataset entries.

AI Response Generation

Model: Google Generative AI (gemini-1.5-flash).

Functionality: Generates contextual responses to enhance engagement.

Implementation:

Function: get_text_response

Leverages the Google Generative AI SDK.

User Interface

Framework: Streamlit

Features input fields for queries, sections for translations, suggestions, and AI responses.

Challenges Encountered

1. Deployment Issues

Missing API key configuration on Streamlit Cloud.

Resolution: Added API keys using Secrets Manager.

2. Dependency Management

Missing dependencies (e.g., google-generativeai, pandas).

Resolution: Created a requirements.txt file.

3. Dataset Accuracy

Limited dataset size led to untranslated or incomplete suggestions.

Resolution: Expand the dataset with more phrases and translations.

Strengths

Cultural Preservation: Makes Burushaski accessible to a broader audience.

AI Integration: Advanced conversational capabilities.

Scalability: Modular design allows for future feature enhancements.

Limitations

Dataset Dependency: Restricted to available phrases in the dataset.

Network Dependency: AI responses require a stable internet connection.

Latency: Potential delays during heavy server loads or poor connectivity.

Future Enhancements

Dataset Expansion: Add more phrases and idiomatic expressions.

Voice Input/Output: Enable speech recognition and text-to-speech.

Offline Mode: Develop offline functionality with pre-trained models.

Error Handling: Improve user guidance for unresolved issues.

How to Run the Project

Clone the repository from GitHub: Burushaski ChatBot GitHub.

Install dependencies:

pip install -r requirements.txt

Run the Streamlit application:

streamlit run app.py

Access the application through the URL provided by Streamlit.

Contact

Developer: Saliha NIshat 
Email: salihanishad321@gmail.com

Conclusion

The Burushaski ChatBot is a pioneering tool for language preservation and cultural exchange. 
By integrating translation capabilities with AI-powered interactions, it offers a robust platform for both native speakers and language enthusiasts. 
With ongoing development and dataset enrichment, the project has strong potential for significant impact.

