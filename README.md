# CardGen.ai — גנרטור קלפים

A free, open-source card generator for Hebrew word-guessing party games.

🌐 **Live site:** [https://noroz123n.github.io/cardgen.ai](https://noroz123n.github.io/CardGen.ai/)

## Features

- 700+ Hebrew words across 12 categories
- Category filtering and difficulty levels (easy / medium / hard)
- 6 card color themes + random mode
- AI card generation via Google Gemini API (free tier)
- API key saved locally in your browser — never sent to any server
- Optional login/signup — stored entirely in localStorage, no backend
- Print-ready layout
- Mobile friendly

## How to use

Just open `CardGenAI.html` in any browser. No build step, no dependencies, no server.

## Hosting on GitHub Pages

1. Fork or upload this repo
2. Go to Settings → Pages → Deploy from branch (main, root)
3. Your site will be live at `https://USERNAME.github.io/REPO_NAME`

## AI Generation

Get a free Gemini API key at [aistudio.google.com](https://aistudio.google.com).
Enter it in the AI panel — it saves locally to your device only.

## Privacy

- No server, no database, no analytics
- All user data (login, API key) stored only in `localStorage` on your device
- Nothing is ever transmitted anywhere except your Gemini API calls (which go directly to Google)

## Legal

This is an independent fan tool for word-guessing party games.  
Not affiliated with, endorsed by, or connected to Tactic Games or the official Alias® brand.  
Alias® is a registered trademark of Tactic Games Oy.

## License

MIT — see [LICENSE](LICENSE)
