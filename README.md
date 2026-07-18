# English Practice Hub

A personal English practice tool (Tagalog/English) with a phrase library, quiz mode, typing drill, voice practice, common mistakes, vocabulary, and idioms — all in one static page. Progress (daily streak) is saved locally in the browser via `localStorage`.

## Run it locally

No build step needed. Just open `index.html` directly in a browser, or serve it with any static server, e.g.:

```
npx serve .
```

## Deploy to Vercel

First-time deploy:

```
cd english-practice-hub
vercel
```

Follow the prompts (link/create a project, accept the defaults — it's a static site, no build command needed).

Future updates:

```
git add .
git commit -m "your change"
vercel --prod
```

(Or push to your connected Git remote if you set one up in the Vercel dashboard — it will auto-deploy on push.)
