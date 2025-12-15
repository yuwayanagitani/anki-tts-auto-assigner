# Anki TTS Auto Assigner

AnkiWeb: https://ankiweb.net/shared/by-author/2117859718

Automatically reads aloud selected fields on your Anki cards — without modifying your card templates. Useful for language learning, accessibility, listening practice, and bilingual study decks.

## Features
- Read selected fields aloud during review
- Works without changing templates by injecting a small playback UI
- Supports local/system TTS and external providers (configurable)

## Requirements
- For cloud/advanced voices: provider API key (if using external service)
- For local TTS: platform TTS support (Windows SAPI, macOS NSSpeech, Linux speech-dispatcher)

## Installation
1. Tools → Add-ons → Open Add-ons Folder.
2. Place the add-on folder into `addons21/`.
3. Restart Anki.

## Usage
- Enable/disable TTS from the add-on menu.
- Choose fields to read in the add-on settings.
- During review the playback button will appear when configured fields are present.

## Configuration
Edit `config.json`:
- provider (system/gcloud/openai-tts/etc.)
- voice, rate, volume
- fields_to_read (array)

Example:
```json
{
  "provider": "system",
  "voice": "default",
  "fields_to_read": ["Front", "Back"]
}
```

## Privacy & Costs
Cloud TTS sends text to provider servers and may incur costs. Use system TTS to avoid external calls.

## Issues & Support
Describe your OS, Anki version, and desired provider when reporting problems.

## License
See LICENSE.
