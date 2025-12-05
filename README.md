# PaperMind

Transform research papers into learning materials — summaries, flashcards, quizzes, audio, and presentation decks.

![PaperMind](https://img.shields.io/badge/version-1.0.0-black) ![License](https://img.shields.io/badge/license-MIT-yellow)

## Features

- **Smart Summary** — 250-word accessible summary of any research paper
- **Flashcards & Quiz** — 25 auto-generated flashcards with quiz mode
- **Audio Summary** — Listen to paper summaries on the go
- **Enhanced Deck** — Presentation slides with:
  - Story arc structure (Problem → Approach → Results → Implications)
  - Auto-generated diagrams (methodology, architecture)
  - Key statistics highlighted
  - Speaker notes
  - Depth options (5 / 10 / 15 slides)
  - Angle options (Technical / Business / General)
  - Export to PowerPoint (.pptx)

## Tech Stack

- React 18
- Gemini API
- PptxGenJS (PowerPoint export)
- Mermaid (diagrams)
- Web Speech API (audio)

## Getting Started

### Prerequisites

- [Gemini API Key](https://aistudio.google.com/apikey) (free)

### Local Development

1. Clone the repository
```bash
git clone https://github.com/yourusername/papermind.git
cd papermind
```

2. Serve locally
```bash
npx serve .
```

3. Open `http://localhost:3000`

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/papermind)

Or manually:
1. Push to GitHub
2. Import repository in [Vercel](https://vercel.com/new)
3. Deploy (no configuration needed)

## Usage

1. Enter your Gemini API key (stored locally in browser)
2. Upload a PDF or paste an arXiv link
3. Select output type: Summary, Flashcards, Audio, or Deck
4. For decks, choose depth and angle before generating

## Configuration

API keys are stored in browser localStorage and never sent to any server except Google's Gemini API.

## Roadmap

- [ ] Paper digest email subscription
- [ ] Personal library (save papers)
- [ ] Chat with paper
- [ ] Tweet thread generator

## License

MIT License — see [LICENSE](LICENSE) for details.

## Contributing

Pull requests welcome. For major changes, open an issue first.
