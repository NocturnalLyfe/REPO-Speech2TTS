==================================================
    REPO Speech-to-TTS Mod v1.0
    by Nocturnal
==================================================

DESCRIPTION:
Converts your voice chat into text-to-speech for fun!
Uses offline speech recognition - no internet required.

REQUIREMENTS:
- BepInEx 5.4.x or higher
- REPO game

INSTALLATION:
1. Make sure BepInEx is installed in your REPO game folder
2. Extract the entire "Nocturnal-SpeechToText" folder to:
   REPO/BepInEx/plugins/
3. Launch the game and join a voice chat lobby

USAGE:
- Your voice will automatically be converted to TTS
- Press F7 to toggle STT on/off at any time
- When disabled, your normal voice is transmitted

FOLDER STRUCTURE:
REPO/
└── BepInEx/
    └── plugins/
        └── Nocturnal-SpeechToText/
            ├── SpeechToText.dll
            ├── libvosk.dll
            ├── (other DLLs)
            └── model/
                └── vosk-model-small-en-us-0.15/

CONTROLS:
F7 - Toggle Speech-to-Text ON/OFF

TROUBLESHOOTING:
- Check BepInEx/LogOutput.log for errors
- Make sure all DLLs are in the same folder
- Verify the model folder is named exactly "vosk-model-small-en-us-0.15"
- Model must be inside the "model" subfolder

NOTES:
- Model file is ~40MB
- Works completely offline
- May have slight delay during transcription
- Accuracy depends on microphone quality and speech clarity

For better accuracy, download the larger model:
vosk-model-en-us-0.22 (128MB)
From: https://alphacephei.com/vosk/models

==================================================