# LIFT 2027

Event site for **LIFT 2027 — Leaning Into Fault Tolerance**, organised by Planckian. 22–26 March 2027, Aula Dini, Palazzo del Castelletto (Scuola Normale Superiore), Pisa.

## Files

- `index.html` — event page (speakers, programme topics, contribute, sponsors, contact)
- `submit.html` — abstract submission form for contributed talks and posters
- `ds/` — Nocturne design system, retuned to the Planckian palette (navy, coral, violet): `styles.css` (all design tokens) and `_ds_bundle.js`
- `assets/` — logo and sponsor/institution marks
- `support.js` — runtime the two pages load

## Publishing

Settings → Pages → Deploy from a branch → `main` / root. The pages are static and use relative paths, so they also work from a subdirectory.

The site is served at https://liftconference.org (the `CNAME` file). The domain is registered at Namecheap. Its DNS (Advanced DNS) has four `A` records on `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`, plus a `CNAME` record from `www` to `lantanotrinidad.github.io`.

## Editing

Both pages are single files: markup at the top, a `Component` class at the bottom holding form validation and the calendar download. Colors, type and spacing come from `ds/styles.css` variables — change tokens there rather than hard-coding values.

The only public contact is lift2027@planckian.co, a Google group all three chairs can reply from. Submission emails go there too. The "Add to calendar" file links to https://liftconference.org.
