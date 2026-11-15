# NovaBridge

NovaBridge is a free, browser-based Business Starter Assistant for entrepreneurs and small businesses. It uses built-in JavaScript templates to create first drafts of a business tagline, business description, social media bio, and promotional message from a business name, activity, customer group, and main benefit. It does not use AI or contact a server to generate results.

The form requires all four fields. Blank and whitespace-only entries are rejected, with an inline message linked to each field and focus moved to the first invalid field. Generated copy is a starting point: review the wording and verify claims before using it.

## Privacy

The page processes form entries and generates drafts in the browser. It does not send those entries to a server or store them. If you choose **Copy all results**, the browser writes the generated text to the clipboard. The contact links open a Gmail compose page addressed to NovaBridge; they do not include or attach form entries.

## Project files

- `index.html` contains the complete static site, styles, form, and template logic.
- There is no build step, package manifest, or automated test framework in this project.
