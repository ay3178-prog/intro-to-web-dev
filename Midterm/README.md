# Lost in Translation (Midterm)

**Live site:** https://ay3178-prog.github.io/intro-to-web-dev/Midterm/

## Concept
A blog about learning languages, told through my own stories of speaking in English, Hindi, Spanish, Turkish and Italian (which I'm learning now). It's for language lovers and for anyone who freezes up when it's their turn to speak. Speaking someone's language is a way of respecting where they come from, so that nothing gets lost in translation.

## Sitemap
```
Home
├── Blog      (stories grouped by language)
│     └── Languages dropdown jumps to #hindi, #spanish, #turkish, #italian
└── About     (me + contact)
```
Every page: logo (links home), nav, footer with socials and email/bsically has a footer.

## Wireframe
![Home page wireframe](img/wireframe.png)

## Skills used
- Box model, flexbox and positioning (header, hero, three-column section, explore cards)
- CSS-only dropdown nav (Week 05 pattern)
- Hero with text over the image
- Explore cards with a hover mask
- CSS variables for my color palette
- Media query at `max-width: 768px`: nav stacks, columns become one, story previews always show

## Progress
- Home page: built (sticky nav with dropdown, hero with music player, moving photo strip, why languages cards, explore cards with hover previews)
- Blog page: built, stories still to write
- About page: built (about me + contact form)

## Skills used
- Box model, flexbox and positioning
- CSS-only dropdown nav (Week 05) that fades in
- Hero with text over the image
- Hover effects: underline, button lift, card zoom, sliding story previews
- Keyframe animations: hero text rises in, hero photo slowly zooms, photo strip scrolls like a carousel
- Contact form (Week 07)
- CSS variables for my colors
- Media query at max-width 768px, plus prefers-reduced-motion for people who turn off animations

## File structure
```
Midterm/
├── index.html      home page
├── blog.html       blog, grouped by language
├── about.html      about me + contact
├── css/
│   ├── var.css     my colors + fonts (variables)
│   └── xstyle.css  all the styling
├── img/            photos
├── audio/
│   └── foreign.mp3 song for the music player on the home page
└── README.md
```

## Sources
- W3Schools, HTML Audio: https://www.w3schools.com/html/html5_audio.asp (used for the music player in the hero)
- Music: "Foreign" by Moavii, from freetouse.com
- Class exercises: Week 04 flexbox, Week 05 dropdown nav and portfolio page, Week 06 media queries
- Fonts: Google Fonts (Courier Prime, DM Sans)
- Photos: [list where each photo came from]

## Next steps
- Write a real story for each language
- Connect the contact form

## Credits
Photos: google