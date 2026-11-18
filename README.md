# NovaBridge

NovaBridge is a static website with free browser-based business tools and practical service pages for bookkeeping and monthly reporting, business documents and invoicing, and accounting software setup. It includes a basic enquiry flow, downloadable business resources, and page-sharing controls.

## Privacy

The free tools process entries in the browser. The weekly tracker stores records in local storage on the user's device. The enquiry form does not submit to a server or store details; it prepares a Gmail draft link only after the visitor requests one. Opening that link sends the entered details to Google to create the draft. They are sent to NovaBridge only if the visitor reviews and sends it. Visitors are told not to include sensitive financial or employee records.

## Search and sharing

The site includes page-specific titles and descriptions, canonical and social preview metadata, `sitemap.xml`, and `robots.txt`. Search engines may take time to discover and index updated pages. Sharing uses the browser's native share sheet where available and clipboard copying as a fallback.

## Project files

- `index.html` is the home page and toolkit.
- `bookkeeping.html`, `business-documents.html`, and `accounting-software.html` are service pages.
- `resources.html` is the free resource library.
- `monthly-records-checklist.csv`, `invoice-follow-up-templates.txt`, and `weekly-business-review.csv` are downloadable resources.
- `sitemap.xml` and `robots.txt` support search discovery.
- The project is static and has no build step, backend, or automated test framework.
