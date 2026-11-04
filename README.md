# DontSleepMarketing site

The DontSleepMarketing website: a single-page motion site for a Houston social media and motion studio. As you scroll, a pair of watching eyes blooms out of the dark, freezes the page, then stays in the background.

## What's here

- `index.html`: the whole site (styles, markup, and scripts in one file). Fonts load from Google Fonts.
- `media/`: the Trill Burgers National Burger Day reel and kitchen promo (web-compressed MP4s) with poster frames.

## Deploy

**Netlify (recommended):** Add new site → Import from Git → pick this repo. No build command, publish directory `/`. The "Wake me up" form is set up for Netlify Forms, so requests show up under Forms in the Netlify dashboard (turn on email alerts in Forms → Form notifications).

**Vercel / Cloudflare Pages:** import the repo with no build step. The page works, but the contact form needs a form service (such as Formspree) since Netlify Forms only works on Netlify.

**GitHub Pages:** Settings → Pages → Deploy from branch → `main` / root. Same note about the form.

## Editing

Copy for each section lives in plain HTML inside `index.html`. The eye animation is the `frame()` and `drawEye()` functions in the script at the bottom; the scroll timing for each moment is commented at the top of that block.
