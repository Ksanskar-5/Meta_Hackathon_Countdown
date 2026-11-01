# Meta AI Hackathon — Submission Countdown

Live countdown to the **Meta Global AI Developer Hackathon** project submission deadline.

**Deadline: November 4, 2026 at 9:00 PM ET** ([official event page](https://cerebralvalley.ai/e/meta-ai-developer-hackathon))

## Run

It's a single zero-dependency file. Just open it:

```sh
open index.html
```

or serve it:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Publish to GitHub Pages

```sh
git add index.html README.md
git commit -m "Add submission countdown"
git push -u origin main
```

Then in the repo: **Settings → Pages → Deploy from branch → `main` / `/ (root)`**.
Your link will be `https://KsanskaR-5.github.io/Meta_Hackathon_Countdown/`.

## Details

- `index.html` (~9 KB) — the whole app: hours countdown and progress bar. No frameworks, no external requests, no build step.
