[README.md](https://github.com/user-attachments/files/32389734/README.md)
# Crossroads Guide

Mobile-first Crossroads class guide for October 2026.

## Updating the next Crossroads session

Most recurring content lives in `crossroads-data.js`:
- session label, dates, times, registration URL, opening note
- campus names and addresses
- class titles, leaders, descriptions, tags, capacity and requirements

The visual presentation and interaction live in `index.html`.

## Logo

The current header uses a simple CSS recreation of the Crossroads X mark and wordmark. Replace the `.brand` block with the official SVG/PNG when available without changing the rest of the layout.

## Registration URL

The current CTA points to `https://www.yorkalliance.org/crossroads` because the direct Church Center registration URL was not present in the source PDF text. Replace `session.registrationUrl` in `crossroads-data.js` with the direct registration URL once available.
