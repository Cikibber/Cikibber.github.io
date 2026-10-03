# Wesley Maximillian Lay · Portfolio

Personal portfolio styled after the **Persona 3 Reload** pause menu. Pure HTML, CSS, and JavaScript, with no build step.

Design by [Aiosssss](https://github.com/Aiosssss/porto-persona3) & Wesley. This website is inspired by P3R; Persona 3 Reload is © ATLUS / SEGA.

## Run locally

```sh
python -m http.server 8000
# open http://localhost:8000
```

Deep links for testing: `?page=project`, `?page=experience`, `?page=skills&tab=web`, `?page=about`, `?page=contact`.

## Editing content

All project, skill, and menu data lives at the top of `js/main.js`:

- `experienceData`: EXPERIENCE screen cards (work history from the CV), same detail card on ENTER.
- `slinkData`: Social Link project cards. `rank` is shown on the card ("MAX" = shipped), and ENTER opens the detail card built from `desc`, `highlights`, `stack`, and `url`.
- `skillTabsList` / `skillGroupsData`: SKILLS tabs and stat bars.
- About and Contact copy live in `index.html`.
