Friday-AI-Project/
│
├── main.py                     # Entry point for the GUI (GraphicalUserInterface is called here)
├── .env                        # Environment variables file (e.g., Assistantname=friday)
├── Requirements.txt
│
├── Backend/
│   ├── Automation
│   ├── Chatbot
│   ├── ImageGeneration
│   ├── Model
│   ├── RealtimeSearchEngine
│   ├── SpeechToText
│   └── TextToSpeech
│
├── Frontend/
│   ├── Graphics/
│   │   ├── Friday.gif
│   │   ├── Home.png
│   │   ├── Chats.png
│   │   ├── Mic_on.png
│   │   ├── Mic_off.png
│   │   ├── Minimize2.png
│   │   ├── Minimize.jpg        # (Consider renaming to Restore.png for clarity)
│   │   ├── Maximize.png
│   │   ├── Close.png
│   │   └── voice.png
│   │
│   └── Files/
│   │   ├── Mic.data            # True/False microphone state
│   │   ├── Status.data         # Assistant status text (live speech input)
│   │   └── Responses.data      # Chat messages or answers
│   │
│   └── GUI.py
│
├── Data/
│
└── README.md                   # Optional: documentation for setup and usage
