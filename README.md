# LIFT 2027

Event site for **LIFT 2027 — Leaning Into Fault Tolerance**, a Planckian conference hosted by the Scuola Normale Superiore. 22–26 March 2027, Aula Dini, Palazzo del Castelletto, Pisa.

## Files

- `index.html` — event page (speakers, programme topics, contribute, sponsors, contact)
- `submit.html` — abstract submission form for contributed talks and posters
- `ds/` — Nocturne design system, retuned to the Planckian palette (navy, coral, violet): `styles.css` (all design tokens) and `_ds_bundle.js`
- `assets/` — logo and sponsor/institution marks
- `support.js` — runtime the two pages load

## Publishing

Settings → Pages → Deploy from a branch → `main` / root. The pages are static and use relative paths, so they also work from a subdirectory.

## Editing

Both pages are single files: markup at the top, a `Component` class at the bottom holding form validation and the calendar download. Colors, type and spacing come from `ds/styles.css` variables — change tokens there rather than hard-coding values.

Submission emails currently go to loftelie@planckian.co, cc roberto.menta@sns.it and tlantano@planckian.co.
