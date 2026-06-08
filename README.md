# Kabuya

Website for Kabuya B.V. — Strategy, Finance & Investments.

Built with plain HTML, CSS and vanilla JavaScript. No framework, no build step.

## Setup

1. Clone the repo
2. Open `index.html` in a browser — that's it locally

## Contact form

The contact form uses [Formspree](https://formspree.io) to forward submissions to your email without exposing your address.

To activate it:
1. Sign up at formspree.io
2. Create a new form
3. Copy your form ID (looks like `xabcdefg`)
4. In `index.html`, find this line and replace `YOUR_FORM_ID`:

```js
const res = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) and import the repo
3. Vercel auto-detects static HTML — no config needed
4. Add your custom domain (kabuya.eu) in the Vercel dashboard
5. Point your domain's DNS to Vercel by adding the records shown in the dashboard

## To do

- [ ] Replace `YOUR_FORM_ID` with real Formspree ID
- [ ] Update LinkedIn URL in contact page
- [ ] Update KvK number in footer
- [ ] Add About page with bio and photo
