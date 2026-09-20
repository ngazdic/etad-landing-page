# ETAD Landing Page

Personal training for women in Abu Dhabi — a landing page for Exclusive Trainers Abu Dhabi (ETAD), rebuilt from the live site's content and matched to its black/gold brand.

## Files

- **`index.html`** — the full standalone page (can be opened directly in a browser, or deployed as-is to any static host).
- **`wordpress-snippet.html`** — the same page with the `<title>` tag stripped, ready to paste straight into a WordPress **Custom HTML** block (Gutenberg) or an HTML widget (Elementor/Divi). Use a blank/canvas page template so the theme's own header/footer don't double up with this page's built-in ones.

## Notes

- Images are hotlinked from the current live site (`personal-training-for-women.komericki.workers.dev`). Replace those `src` URLs with your own WordPress Media Library uploads once you're happy with the page, so it doesn't depend on the old site staying up.
- The 6-step "find my starting point" quiz on the page builds a WhatsApp message from the visitor's answers via `wa.me`.
