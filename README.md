# Task-Restaurant-site

To make a professional restaurant website.

## Local environment

If you use any Gemini-based terminal automation locally, store the key in a `.env` file in this folder.

Example:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

## Repeatable push workflow

Use this sequence for future updates:

```powershell
git status
git add .
git commit -m "Describe your change"
git pull --rebase origin main
git push origin main
```

## Security note

Keep `.env` out of Git so API keys stay local and are never published to GitHub.
