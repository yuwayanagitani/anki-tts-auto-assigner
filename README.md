# Anki TTS Auto Assigner

🔗 **AnkiWeb**  
https://ankiweb.net/shared/info/474218374

---

## What this add-on does

**Anki TTS Auto Assigner** automatically assigns **Text-to-Speech (TTS) tags** to notes based on their fields,  
so that Anki can generate spoken audio **without manually editing each card**.

It is designed to make TTS usage **automatic, consistent, and scalable**, especially for large decks.

---

## Core Features

- 🔊 Automatically adds TTS tags to notes
- 📝 Works based on **field content** (e.g. Question / Answer)
- 🌍 Language-aware assignment (per field)
- 🔁 Supports batch processing
- 🪶 Lightweight: no audio files are generated or stored
- ⚙️ Uses Anki’s built-in TTS engine (no external services)

---

## How It Works

1. You select notes (or run it on a target set)
2. The add-on inspects configured fields
3. Appropriate TTS tags are inserted automatically
4. Anki handles playback using its native TTS system

This means:
- No MP3 files
- No media folder bloat
- Instant playback on supported platforms

---

## Why Use Auto TTS Assignment?

Manually adding TTS tags is:

- Time-consuming
- Error-prone
- Inconsistent across large decks

This add-on ensures:

- Uniform TTS formatting
- Fast setup for thousands of notes
- Easy maintenance when note types change

---

## Installation

### From AnkiWeb (recommended)

1. Open Anki  
2. Tools → Add-ons → Get Add-ons  
3. Enter the code from AnkiWeb  
4. Restart Anki  

👉 https://ankiweb.net/shared/info/474218374

---

### Manual (GitHub)

1. Download or clone this repository
2. Place it in:

   `Anki2/<profile>/addons21/anki-tts-auto-assigner/`

3. Restart Anki

---

## Configuration

Open:

**Tools → Add-ons → Anki TTS Auto Assigner → Config**

You can configure:

- Enable / disable the add-on
- Target note type(s)
- Field → language mapping
- TTS voice options (per language, if supported)
- Whether to overwrite existing TTS tags

All settings are applied **without modifying card templates manually**.

---

## Usage

### Automatic assignment

- Run the add-on on selected notes
- TTS tags are added immediately
- Changes are visible in the note fields

### Batch use case

Ideal when:
- Importing large decks
- Cleaning up inconsistent TTS tags
- Adding pronunciation support after deck creation

---

## Notes & Limitations

- This add-on **does not generate audio files**
- Actual playback depends on:
  - Platform (Windows / macOS / Linux)
  - Available system voices
- Some voices or languages may not be available on all systems

---

## Performance

- Operates only on selected notes
- No background tasks
- Safe to run on large collections

---

## Compatibility

- Anki 24.x
- Anki 25.x
- Windows / macOS / Linux

---

## License

MIT License

---

## Author

Created by **@yuwayanagitani**

---

## Related Add-ons

- **AI Card Translator** – Translate cards during review
- **AI Card Explainer** – Generate explanations automatically
- **HTML Exporter for Anki** – Export cards to HTML / PDF

These tools can be combined for a richer, more accessible study workflow.
