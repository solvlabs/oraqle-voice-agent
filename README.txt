ORAQLE Voice AI Agent - v1 (Dec 10, 2025)What It Does: A voice-activated AI agent that listens for "Hey ORAQLE", transcribes speech with Whisper, thinks with Grok/OpenAI, and responds in Rachel's voice via ElevenLabs. Built from scratch with Patrick Duffy—because "it's alive!"Quick Setup (5 Minutes):Unzip to a folder.
Open Terminal, cd to the folder: cd /path/to/ORAQLE-Agent-v1.
Install libs: pip install elevenlabs openai-whisper speechrecognition pydub grokapi.
Edit oraqle_agent.py: Swap in your ElevenLabs API key (line ~8) and Grok API key (line ~9).
Run: python3 oraqle_agent.py.
Say "Hey ORAQLE, tell me a joke" to test—mic permission pops up, grant it.

Keys Needed:ElevenLabs (TTS): elevenlabs.io > Profile > API Keys (free tier: 10k chars/month).
Grok (Brain): x.ai/api (free for starters).

Voices: Rachel ID = "21m00Tcm4TlvDq8ikWAM" (swap in code for Adam: "JBFqnCBsd6RMkjVDRZzb").Troubleshooting:No mic? Install pip install pyaudio.
No sound? Check volume or add save(audio, "response.mp3") after play() to save files.
Errors? Ask Grok: "Fix my ORAQLE agent [paste error]".

Future Ideas: Add weather API, smart home integration, or a GUI. Fork on GitHub!Built with love in Cursor on MacBook Pro. Patrick Duffy, Dec 10, 2025
