# Enterprise Landscaping LLC — Website

Single-file static site (index.html — HTML/CSS/JS all in one file, no build step).

## Deploying changes
This repo is connected to Netlify for auto-deploy. Any push to the `main` branch
automatically publishes to the live site within a minute or two — no manual
drag-and-drop needed.

## Making changes
Ask Claude to edit index.html directly, then commit and push the updated file.

## Before full launch, still needed
- Real business phone number and email (currently placeholders in the Contact
  section and in the page's structured data / JSON-LD block)
- Real domain name in the `<link rel="canonical">` and Open Graph tags in
  the `<head>` (currently placeholder REPLACE-WITH-YOUR-DOMAIN.com)
- Enable Form Detection in Netlify (Site configuration → Forms) so the
  contact form actually captures submissions
