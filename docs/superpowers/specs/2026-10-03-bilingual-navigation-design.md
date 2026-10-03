# YXHTL bilingual navigation design

## Goal

Let English-speaking visitors understand the YXHTL game-guide directory while preserving the existing Chinese homepage.

## Design

- Keep `https://yxhtl.com/` as the Chinese homepage.
- Add an English page at `https://yxhtl.com/en/` with a visible language switch linking both versions.
- Keep the same guide cards and visual style; send English visitors to the English RimWorld route, and explain that Len's Island uses an in-page language toggle.
- Add self-canonical URLs, reciprocal `hreflang` links, and both URLs to the sitemap.
- Add the existing GA4 tag (`G-HM32STKNVV`) to both language pages. Do not create a separate data stream for the navigation site.
- Do not add automatic language redirects.

## Validation

Preview both routes locally at desktop and mobile widths; verify language links, canonical and hreflang metadata, sitemap entries, and one GA4 tag initialization per page before release.
