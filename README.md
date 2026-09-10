# skyXfit — Fitness Calculator

A single-file website: enter age, height, weight, sex, activity level and goal (Fat Loss / Weight Loss / Cutting / Bulking), and it shows BMI, estimated body-fat %, BMR, maintenance calories, a daily calorie target, and a protein/carb/fat macro split. Everything runs in the browser — no backend, no build step, no dependencies to install.

The "Subscribe on YouTube" link near the bottom already points at `https://www.youtube.com/@AkashAinavilli` — update it in `index.html` if the channel URL ever changes.

## Deploy it (pick one)

**Netlify (easiest, free, ~1 minute)**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `skyxfit` folder onto the page
3. You get a live URL immediately. Add a custom domain later from Netlify's site settings if you want one.

**GitHub Pages (free, good if you already use GitHub)**
1. Create a new GitHub repo and push this folder to it
2. In the repo, go to Settings → Pages → set the source to your main branch, root folder
3. Your site publishes at `https://<your-username>.github.io/<repo-name>/`

**Vercel (free, CLI-based)**
1. Install the CLI: `npm i -g vercel`
2. From inside this folder, run `vercel --prod`
3. Follow the prompts — it gives you a live URL

## Editing

Everything — layout, styles, and calculator logic — lives in the one `index.html` file, so you can hand-edit it or drop it into any AI coding tool for changes. Colors and spacing are defined as CSS variables near the top of the `<style>` block if you want to retheme it later.
