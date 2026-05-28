# Codex Newsletter Visual Guide

Public, noindex review site for a Traditional Chinese beginner tutorial:

- How to understand Codex with no IT background
- How to install Codex from direct official Windows and macOS download links
- How to prepare a safe project folder
- How to use Codex with InfoCenter newsletter export reports
- How to analyze opens, clicks, delivery, bounces, complaints, ISP distribution, and link click details

The page is intentionally static and can be deployed directly to Vercel.

## Review Controls

- `index.html` includes `noindex,nofollow,noarchive`
- `robots.txt` blocks crawling
- `vercel.json` adds `X-Robots-Tag`

These controls reduce search indexing. They do not make the URL private.
