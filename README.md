# Best AI for Podcasters

12th site in the Discus lead-gen network.

- Hero CTA: Descript (transcript-as-edit DAW, used by 3M+ podcasters)
- Audience: solo podcasters, interview-show hosts, B2B podcast producers
- Live: https://aldow3n-a11y.github.io/best-ai-podcasters/
- 20 tools across 6 categories

## Build

Pure HTML/CSS/JS. No build step. Open `index.html` locally to preview.

## Deploy

GitHub Pages from `main` branch, root path.

```bash
git init && git add . && git commit -m "initial"
gh repo create aldow3n-a11y/best-ai-podcasters --public --source=. --push
gh api -X POST repos/aldow3n-a11y/best-ai-podcasters/pages --input - <<EOF
{"source":{"branch":"main","path":"/"}}
EOF
```
