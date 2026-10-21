# Static Layout: Eleven Fifty Academy Homepage Clone

My first coding project!

I built it in February 2020 as the **Gold Badge** project for the Eleven Fifty Academy coding bootcamp. The assignment was to recreate the layout of a real website with plain HTML and CSS, and I picked the Eleven Fifty Academy homepage. I keep it up as a token to remember how far I've come :)

**Live site:** https://corynnem.github.io/static-layout/

## What's in it

- **A fixed navigation bar** with the logo, a search icon, nav links and a highlighted "Get Started" button
- **A full-width hero section** with a looping background video, the "RECODE YOUR FUTURE" headline and a "Find Your Course" button
- **A "Course Information" section** with three cards (Free Intro, Full-Time and Part-Time courses), each with a hover shadow and a call-to-action button

## Built with

- HTML5
- CSS3: Flexbox, `position: fixed/absolute`, hover states and box shadows
- Google Fonts (Overpass)

No frameworks, build tools or JavaScript. It's just as it says: A Static Layout! 

## Running it

There's nothing to install. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/corynnem/static-layout.git
cd static-layout
open index.html        # macOS. On Windows use: start index.html
```

## Project structure

```
static-layout/
├── index.html          # Page markup
├── staticProject.css   # All styles
└── assets /            # Logo, search icon and other images (the folder name ends with a space)
```

## Status (checked October 2026)

The page still opens and the local images load, but some of it has broken over time:

- **The hero video and its poster image no longer load.** They were hot-linked from elevenfifty.org, and those files now return 404. Without the video, the headline and button slide up and overlap the nav bar.
- **Several nav links now point to pages that no longer exist** (Get Started, Employers, Admissions).
- **The layout is desktop-only.** The course section is 130% wide, so the page scrolls sideways, and it isn't responsive on phones.

I've left the code as it was in 2020 so the repo shows where I started.
