# Suggested Project Structure

Use this structure unless your instructor approves a different organization.

```text
lost-in-the-scroll/
├── index.html
├── reflection.html
├── styles/
│   ├── tokens.css
│   ├── layout.css
│   └── animations.css
├── scripts/
│   └── main.js
├── assets/
│   ├── svg/
│   └── images/
└── README.md
```

## Notes

- Load `tokens.css` before other style files.
- Keep all GSAP + ScrollTrigger + ScrollSmoother logic in `scripts/main.js`.
- Keep asset file names clean and predictable (`chapter-01.svg`, `hero-bg.webp`, etc.).
