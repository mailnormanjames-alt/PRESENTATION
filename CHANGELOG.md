# Changelog

## v1.8 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Updated all 10 Hair Masters card links from relative paths (`../THE-*`) to live Vercel deployment URLs (`https://hair-masters-nine.vercel.app/THE-*/`).

## v1.7 — July 1, 2026
**Files:** All
- Pushed to GitHub: https://github.com/mailnormanjames-alt/PRESENTATION.git; added .gitignore blocking ZIP files, OS files, and node_modules.

## v1.6 — July 1, 2026
**File:** `PRESENTATION/HOVER-EFFECTS-REFERENCE.txt`
- Created hover effects reference guide documenting 20+ reusable CSS hover effects for cards, images, text, and overlays; includes 5 ready-to-use combined card styles with full code snippets and project notes.

## v1.5 — July 1, 2026
**Files:** `PRESENTATION/master-index.html`, `PRESENTATION/images/cafe/`
- Downloaded 10 cafe cover images locally from individual project folders (GitHub raw CDN was rate-limiting the F&B covers folder); updated img src to local paths with correct extensions (.jpg/.png); increased card brightness from 0.4 to 0.65.

## v1.4 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Updated Cafe Masters section with 10 live Vercel project links and correct project names (The Embassy, La Equinox, Rust & Roast, The Altitude, The Atelier Studio, The Garden, The Roast, The Noir, The Oasis, The Observatory).

## v1.3 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Fixed 10th card visibility bug: replaced `gsap.from()` with `gsap.set()` + `gsap.to()` using `once: true` on all ScrollTriggers to prevent cards from remaining at `opacity: 0`.

## v1.2 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Changed sticky nav brand text from "Masters" to "Empathy Studio".

## v1.1 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Added GSAP 3.12.5, ScrollTrigger, and Lenis smooth scroll via CDN; implemented hero parallax, card stagger reveals, section header animations, custom cursor, and scroll-spy nav driven by Lenis events.

## v1.0 — July 1, 2026
**File:** `PRESENTATION/master-index.html`
- Created master presentation page with 6 collections (Hair Masters, Look-Book Masters, Cafe Masters, Yoga Masters, Restaurant Masters, Occult Masters) totaling 60 cards, sticky navigation, and responsive layout.
