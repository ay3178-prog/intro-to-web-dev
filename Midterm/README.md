# Lost in Translation (Midterm)

**Live site:** https://ay3178-prog.github.io/intro-to-web-dev/Midterm/

## Concept
A blog about learning languages, told through my own stories in English, Hindi, Spanish, Turkish and Italian (which I'm learning now). It's for language lovers and for anyone who freezes up when it's their turn to speak. Speaking someone's language is a way of respecting where they come from, so nothing gets lost in translation.

## Sitemap
```
Home
├── Blog      (stories grouped by language)
│     └── Languages dropdown jumps to #hindi, #spanish, #turkish, #italian
├── About     (me)
└── Contact   (contact form)
```
Every page: logo (links home), nav, footer with socials and email.

## Wireframe
The home page wireframe is in my presentation slides.

## Skills used
- Box model, flexbox and positioning (header, hero, three-column section, explore cards)
- CSS-only dropdown nav (Week 05 pattern)
- Hero with text over the image
- Explore cards with a hover mask
- CSS variables for my color palette
- Media query at `max-width: 768px`: nav stacks, columns become one, story previews always show

## Progress
- Home page: beach hero with a music player, intro with my photo, a carousel of the blog photos (click one to jump to that story), why languages, phrases, and a contact band
- Blog page: four full stories next to their photos, the photos zoom and show the place name on hover
- About page: my photo and bio
- Contact page: contact form in a box on a rust background

## File structure
```
Midterm/
├── index.html      home page
├── blog.html       blog, grouped by language
├── about.html      about me
├── contact.html    contact form
├── css/
│   ├── var.css     my colors + fonts (variables)
│   └── xstyle.css  all the styling
├── img/            hero-beach, india, spain, harbor, italy, aparna (.jpg)
├── audio/
│   └── foreign.mp3 song for the music player on the home page
└── README.md
```

## Sources
- W3Schools, HTML Audio: https://www.w3schools.com/html/html5_audio.asp (used for the music player in the hero)
- Music: "Foreign" by Moavii, from freetouse.com
- Class exercises: Week 04 flexbox, Week 05 dropdown nav and portfolio page, Week 06 media queries
- Fonts: Google Fonts (Courier Prime, DM Sans)
- Pictures: Google
