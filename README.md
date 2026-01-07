# tldgaf.com

> too long; don't give a fuck

A minimalist web app that displays randomized cheeky responses to send when someone sends you a wall of text. Built with an ironically classy aesthetic.

## What is this?

Send this link to friends when they send you excessively long articles, documents, or messages. Each page load displays a random crude variation of "TL;DR" with style.

## Contributing

Got a creative way to say "I'm not reading that"? We'd love your contributions!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new messages.

## Tech Stack

- Pure HTML/CSS/JavaScript (zero dependencies)
- Playfair Display serif font
- Deployed on Vercel
- Total size: ~5KB

## Local Development

No build process needed. To test locally:

```bash
# Python 3
python3 -m http.server 8000

# Or Node.js
npx serve

# Or any static file server
```

Then visit http://localhost:8000

## Deployment

Automatically deploys to Vercel when pushing to the `main` branch. To deploy your own:

1. Fork this repository
2. Connect it to Vercel
3. Deploy (zero configuration required)
4. Add your custom domain in Vercel settings

## License

MIT
