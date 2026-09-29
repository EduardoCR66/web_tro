# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS, no framework or build step. Tailwind CSS via the Play CDN (`cdn.tailwindcss.com`), Google Fonts (Oswald + Inter) via `<link>`, vanilla JS for interactivity (mobile menu, scroll-reveal via IntersectionObserver, counters, lightbox). Multi-page site: `index.html`, `sobre-tro.html`, `encuentranos.html`, sharing assets under `assets/img/`. Determined from the existing codebase, not asked.

## Users

Two audiences, served equally, not sequentially:

- **Fleet managers / trucking companies (B2B):** evaluating TRO as an ongoing maintenance and rescue partner for their tractocamión fleet. Longer decision, looking for trust signals (track record, certifications, coverage).
- **Truck drivers in roadside emergencies (urgent, transactional):** stranded or facing a breakdown on the highway, need to act immediately (call or WhatsApp) with minimal friction.

## Product Purpose

Tracto Rescates de Occidente (TRO) is a diesel tractor-trailer (tractocamión) roadside rescue and repair company operating across western Mexico, based in Nuevo México, Jalisco, since 2017. It exists to keep fleets and individual truckers moving: engine repair, roadside rescue, 24-hour mobile workshops, fleet maintenance programs, preventive maintenance, and night rescue coverage. Success means a fleet renews its relationship with TRO and a stranded driver gets rescued fast enough to keep their route.

## Positioning

Coverage and speed: TRO covers "todo occidente… y más allá" (all of western Mexico and beyond) with faster response than regional competitors. This — not price or a single certification — is the claim a neighboring shop could not truthfully copy without matching both the geographic reach and the response time.

## Operating Context

- Founded 2017, based in Nuevo México, Jalisco (C. La Cardona 15A, Marcelino García Barragán, 45134).
- 24-hour mobile workshop units (vans/pickups) dispatched to the roadside, not a fixed-location-only shop.
- Certified diesel technicians; vehicles carry Detroit Diesel, Cummins, and Mercedes-Benz brand certification decals.
- Team of ~20+ uniformed technicians plus office/admin staff, photographed on-site for the marketing site (real team photos, not stock).
- Primary contact channels: phone (33-44-76-35-63), WhatsApp (same number), email (controltro@tractorescatesdeoccidente.com).
- Social presence: Facebook and Instagram, promoted via hashtags #TRO24HRS #SOMOSTRO #RESCATESTRO.

## Capabilities and Constraints

- Confirmed real and not to be altered or re-estimated: 5.1k+ services completed, 15 professionals on staff, operating since 2017.
- Confirmed real content already on the site: mission, vision, and the eight company values (Espíritu de servicio, Honradez/Integridad, Disciplina, Respeto, Compromiso, Excelencia, Profesionalismo, Trabajo en equipo).
- The contact form on `sobre-tro.html` is client-side only — no backend, no email delivery wired up. Any claim of message delivery must stay honest to that (currently shows a local confirmation, does not promise sending).
- No CMS, no server, no build pipeline. All content is hand-authored HTML; images come from real company photos in `assets/img/` (sourced from `img/`), not stock photography.
- No live Instagram feed integration exists (no API/credentials available) — the "hashtag wall" on `encuentranos.html` is a static photo grid using real company photos, not a live embed.

## Brand Commitments

- Name: **Tracto Rescates de Occidente**, abbreviated **TRO**.
- Tagline: "De héroes para héroes."
- Logo: stacked wordmark ("TRACTO RESCATES" over "OCCIDENTE") paired with a red diagonal flag/plus accent mark; no standalone logo file exists, currently reconstructed in HTML/CSS.
- Brand color: red (`#E30613` in current implementation), paired with near-black ink and white.
- Address: C. La Cardona 15A, Marcelino García Barragán, 45134 Nuevo México, Jal., México.
- Phone/WhatsApp: 33-44-76-35-63. Email: controltro@tractorescatesdeoccidente.com.
- Campaign hashtags: #TRO24HRS #SOMOSTRO #RESCATESTRO.

## Evidence on Hand

- Real photography: team group shots, technicians beside branded vehicles, mobile workshop units, and truck fleets, stored in `img/` (originals) and `assets/img/` (site-ready copies).
- Original page mockups under `Mockups/` (header/footer, Bienvenido1-3, Sobre TRO 1-4, Encuentranos 1-2) — the visual and content authority the current three pages were built from.
- No testimonials, case studies, press mentions, or customer logos exist. Do not fabricate any of these for future work.
- No real Instagram post URLs or API access exist — do not present the photo grid on `encuentranos.html` as a live social embed.

## Product Principles

1. Serve both audiences on the same page without making either wait: the fleet manager evaluating a long-term partner, and the driver mid-emergency who needs the call-to-action within reach at all times (hence the persistent floating WhatsApp button).
2. Speed and coverage are the core credibility claim ("todo occidente… y más allá") — never let copy or layout undersell response time or service area.
3. Every claim on the site must trace to real, verifiable content — real photos, real stats, real contact details. No invented testimonials, customer counts, or case studies.
4. 24/7 availability and certified diesel expertise (Detroit Diesel, Cummins, Mercedes-Benz) are operational facts, not just taglines — reflect them concretely in copy and imagery rather than as generic claims.
