# TTS Assigner for Anki

Automatically reads aloud selected fields on your Anki cards — without modifying your card templates. Perfect for language learning, accessibility, listening practice, and bilingual study decks.

## Features
- Text-to-Speech (TTS) playback for selected fields.
- Plays audio on card show, optionally with voice, language, and rate settings.
- No changes required to card templates.

## Requirements
- Anki 2.1+
- Internet connection for cloud TTS providers (if used) or use system/local TTS if supported.

## Installation
1. Download or clone the add-on.
2. In Anki: Tools → Add-ons → Open Add-ons Folder.
3. Place the add-on folder in the add-ons directory and restart Anki.

## Configuration
Available settings (via config UI or `config.json`):
- Fields to read (e.g., Front, Back)
- TTS provider (system/local, or cloud like OpenAI if supported)
- Voice, language, speaking rate, volume
- Play on show / play on demand toggle

Example config:
```json
{
  "fields": ["Front", "Back"],
  "provider": "system",
  "voice": "default",
  "on_show": true
}
```

## Usage
- The add-on will play configured fields automatically when a card is shown.
- You can also trigger TTS manually via the add-on menu or keyboard shortcut (if provided).

## Troubleshooting
- If audio does not play, check system sound and provider credentials.
- Cloud TTS may require API keys; store them securely and follow the provider’s usage rules.

## Development
- PRs and issues welcome. Please include Anki version and steps to reproduce when reporting bugs.

## License
MIT License — see LICENSE file.

## Contact
Author: yuwayanagitani
