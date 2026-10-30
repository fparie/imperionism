# Imperionism — Interlocutor redesign

An understated one-page redesign of imperionism.com for the *Interlocutor* sculpture series.
Bilingual (NL/EN) with a language toggle, a noon–dusk light control, slow ambient motion,
scroll reveals, and a lightbox gallery. All images point at the existing WordPress media library.

## Files

- `index.html` — standalone page; open directly in a browser or host anywhere
- `wordpress/page-interlocutor-redesign.php` — WordPress page template

## Deploying on WordPress

1. Copy `wordpress/page-interlocutor-redesign.php` into your active theme folder
   (`wp-content/themes/<your-theme>/`), e.g. via Appearance → Theme File Editor or your host's file manager.
2. Edit the *Interlocutor* page → in page settings choose Template → **Interlocutor — Redesign** → Update.
3. Reverting is as simple as switching the template back — the existing page content is never touched.

Note: a file added directly to a theme may be removed when the theme updates; move it to a child theme
(or re-upload it) if that happens.
