# English Practice Hub

A personal English practice tool (Tagalog/English) with a phrase library, quiz mode, typing drill, voice practice, common mistakes, vocabulary, and idioms — all in one static page. Progress (daily streak) is saved locally in the browser via `localStorage`.

## Run it locally

No build step needed. Just open `index.html` directly in a browser, or serve it with any static server, e.g.:

```
npx serve .
```

## Deploy to Vercel

This repo is connected to Vercel via GitHub (https://github.com/uixjohnboy-sys/english-practice-hub) — every push to `master` auto-deploys.

To update the live site:

```
git add .
git commit -m "your change"
git push
```

Vercel picks up the push automatically and deploys within a minute or two. Live at: https://english-practice-hub-ashy.vercel.app

You can still deploy manually with the CLI if needed:

```
vercel --prod
```
