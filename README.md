#wyoming-whisper-piper-openwakeword
Documenting my setup of faster-whisper (STT), piper (TTS), openwakeword for Home Assistant 

## Usage 
- Mkdir relevant data directories
```
mkdir -p openwakeword_data
mkdir -p piper_data
mkdir -p whisper_data
```
- `docker compose up -d` 
- This will standup the following services: 
	- Piper (TTS): http://localhost:10200
   	- Faster-Whisper (STT): http://localhost:10300
	- OpenWakeWord: http://localhost:10400 

