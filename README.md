# Yapiri Script — Official Font Repository

**Yapiri** (*footprints*) is an original writing system created for the **Kokborok language** of the Borok people of Tripura, India.

This repository contains the official Yapiri font files, character specifications, and supporting resources.

---

## About Yapiri

Kokborok is the native language of the Borok (Tripuri) people, spoken by over 1 million people in Tripura and across Northeast India. Despite its rich oral tradition, Kokborok has historically lacked a widely adopted native script.

Yapiri was designed to fill that gap — a script built from the ground up to match Kokborok phonology, with clean geometric aesthetics suited for both print and digital use.

The name *Yapiri* means **"footprints"** in Kokborok — each character a step toward reclaiming the written voice of the language.

---

## Features

- 48 characters covering the full Kokborok phonology
- Consonants, vowels, numerals (0–9 + standalone 10), punctuation, and diacritics
- Private Use Area encoding: **U+E000 – U+E02F**
- OpenType GPOS mark-to-base diacritic positioning
- Six kerning classes with optimized spacing
- Clean, geometric design suitable for body text and display use

---

## Character Set

| Category | Count | Codepoints |
|---|---|---|
| Consonants | 28 | U+E000 – U+E01B |
| Vowels | 6 | U+E01C – U+E021 |
| Numerals | 11 | U+E022 – U+E02C |
| Punctuation | 2 | U+E02D – U+E02E |
| Diacritics | 2 | U+E02F + combining |

---

## Installation

### Windows
1. Download `Yapiri.ttf` from the [Releases](../../releases) page
2. Right-click the file → **Install for all users**
3. The font will appear as **"Yapiri"** in any application

### macOS
1. Download `Yapiri.ttf`
2. Double-click → **Install Font**

### Linux
1. Copy `Yapiri.ttf` to `~/.local/share/fonts/`
2. Run `fc-cache -fv`

---

## Usage

Since Yapiri uses Unicode Private Use Area codepoints, you will need to:
1. Have the Yapiri font installed
2. Use the Yapiri keyboard input tool (available at [therealyapiriscript.github.io](https://therealyapiriscript.github.io)) to type in Yapiri
3. Select **Yapiri** as the font in your application

---

## Repository Structure

```
yapiri-font/
├── LICENSE          # SIL Open Font License 1.1
├── README.md        # This file
├── Yapiri.ttf       # TrueType font file
├── Yapiri.otf       # OpenType font file
```

---

## License

This font is released under the **SIL Open Font License 1.1**.
See [LICENSE](LICENSE) for full terms.

The Reserved Font Name is **"Yapiri"** — derivative works must use a different name.

---

## About the Creator

Yapiri was designed by **Animesh Debbarma (TheRealYapiriScript)**, a member of the Borok community of Tripura, as part of an ongoing effort to preserve and digitize the Kokborok language and culture.

- Website: [therealyapiriscript.github.io](https://therealyapiriscript.github.io)
- GitHub: [@TheRealYapiriScript](https://github.com/TheRealYapiriScript)
- Email: therealyapiriscript@gmail.com

---

*Yapiri — footprints of a language finding its written form.*
