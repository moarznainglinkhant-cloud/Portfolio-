# moarz — portfolio

Personal portfolio of **Moarz Naing Lin Khant**, second-year Computer Science Specialist at the University of Toronto.

A single self-contained HTML page: a Pixel Blast–style WebGL background, a working mini zsh (try `help`, then `ls /usr/games`), a swipeable project card stack, and contact links.

## Run it

Open `index.html` in a browser. No build step.

## Edit it

Everything personal lives in config objects at the top of the `<script>`:

- `ME` — name, about, skills, projects, contact
- `BG` — background pixel shape, size and tint
- `HERO` — name animation and name colour
- `NEOFETCH` — logo shown by `neofetch`

Built with GSAP + ScrollTrigger, Geist and JetBrains Mono.
