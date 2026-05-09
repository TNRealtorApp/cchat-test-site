        # BRIEF for worker-style — v1

        - **Type:** feature
        - **Deliverables:** commits
        - **From:** director-tn
        - **Status:** sent
        - **ID:** 2

        ## Objective

        Design and apply the visual styling for the Tennessee Time Travel landing page. Vintage / steampunk-leaning palette (sepia, brass, cream) with strong typography. Mobile-first responsive. Hover and focus states throughout.

        ## Scope (in)

        - styles.css (you create this file)
- index.html — ONLY to add a single <link rel="stylesheet" href="styles.css"> inside <head>

        ## Scope (out — explicitly NOT yours)

        - All other content in index.html (worker-content owns it)
- Any JavaScript
- README.md, Procfile

        ## Constraints (do)

        - Create styles.css at the repo root.
- Add exactly ONE line to index.html: <link rel="stylesheet" href="styles.css"> placed inside <head>.
- Mobile-first: base styles target ~360px width; add a min-width: 720px breakpoint for desktop layout.
- Color palette: deep sepia (#3a2417 or similar) on warm cream (#f5e9d3 or similar); accent brass (#b8893a or similar). Tweak to taste but stay in this family.
- Typography: serif for headings (Georgia or similar), sans-serif for body (system stack).
- Buttons: brass background, cream text, subtle shadow, lift on :hover and :focus-visible.
- Destination cards: bordered, two-column grid on desktop (4 cards across 2 rows), single-column stack on mobile. Hover: slight elevation.
- Booking form: labels above inputs; inputs full-width within container; submit button matches the hero CTA.
- Body max-width ~960px, centered.
- Sufficient color contrast (WCAG AA). Visible :focus-visible outlines on all interactive elements.

        ## Prohibitions (don't)

        - Do NOT change ANY HTML content, structure, or copy. Your only HTML edit is the one <link> line.
- Do NOT add JavaScript.
- Do NOT use external font URLs or remote stylesheets — keep it self-contained.
- Do NOT introduce !important except as a last resort, and explain why in a comment if you must.

        ## Context to read FIRST

        - file:index.html
- artifact:project:PROJECT_MAP.md (if present)

        ## Acceptance criteria

        - styles.css exists at repo root and is linked from index.html.
- Page renders cohesively at 320px wide and 1280px wide (no horizontal scroll, no broken layout).
- All interactive elements (buttons, links, form inputs) have visible :focus-visible state.
- Color contrast for body text and button labels is at least 4.5:1.
- Final commit message references this brief id.

        ## Depends on

        _(none)_
