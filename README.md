# Fixray Email Signature Generator

Gmail-safe email signature builder for the Fixray team. Priority-stripe / ticket-stub design.

**Live:** https://chrisdmorgan.github.io/fixray-email-signature/

## How to use

1. Open the live URL above.
2. Fill in your details (name, title, email, phone, category slug, ticket ID).
3. Click **Copy signature**.
4. In Gmail: ⚙ → See all settings → Signature → paste → Save Changes.

## Design

- Single HTML file, no dependencies.
- Fixray mark embedded as a PNG data URI (Gmail-safe).
- Table-based layout with inline styles (Gmail strips `<style>` blocks).
- System font stack (Inter doesn't load in Gmail — falls back cleanly to `-apple-system` / Segoe UI / Helvetica / Arial).

## Editing

The entire generator lives in `index.html`. Edit locally, commit to `main`, GitHub Pages redeploys automatically.

---

*Fixray · brand/production · V3 (2026-04-20)*
