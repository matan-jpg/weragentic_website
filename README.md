# Matan Website

A plain HTML/CSS/JS one-page business site (Services + Contact). No build step, no dependencies beyond a Google Font — just open `index.html` in a browser to preview, or upload the whole folder as-is to any static host.

## What to fill in before launch

Search each file for the bracketed placeholders and replace with real content:

- `index.html`
  - `[MATAN_BUSINESS_NAME]` (appears in `<title>`, header logo, and footer)
  - `[SHORT_TAGLINE]`, `[ONE_LINE_BUSINESS_DESCRIPTION_FOR_SEARCH_ENGINES]` — used in `<title>`/meta description
  - `[HERO_HEADLINE]`, `[HERO_SUBCOPY]`
  - `[SERVICE_1_TITLE]` / `[SERVICE_1_DESCRIPTION]` (and 2, 3) — swap the inline SVG icons too if a service doesn't fit the placeholder icon
  - `[CONTACT_INTRO]`, `[PHONE_NUMBER]`, `[BUSINESS_ADDRESS]` (email is filled in: support@weragentic.com)
  - `[SHORT_FOOTER_TAGLINE]`
  - The contact `<form>` tag's `action="https://formspree.io/f/REPLACE_WITH_FORM_ID"` — sign up free at formspree.io (or web3forms.com), create a form, and paste in your real endpoint/ID. Without this, the form will not actually send anywhere.

- `css/style.css`
  - `--color-primary` and `--color-accent` at the top of the file — currently a placeholder teal/amber pair. Swap in Matan's real brand colors if he has them.

## Design

The layout, spacing, typography and component patterns (sticky glass header, hover-inverting service cards, floating-label form, rounded soft corners, flat colors with no gradients) were modeled after myfeature.tv's visual style as a reference — colors and all content here are original, not copied.

## Deploying

Any static host works since there's no build step or server code — just upload this folder. Point Matan's existing domain's DNS at whichever host you choose.
