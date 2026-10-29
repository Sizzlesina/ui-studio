# Sources and selective integration

This skill combines reusable design principles with optional guidance from the skills named below. The bundled instructions and references work independently; none of those other skills is required or included. Locate optional skills through the agent's available-skills catalog and read only relevant material if present. Never assume a sibling folder, machine-specific path, or automatic dependency installation. If a skill is absent, continue with UI Studio's bundled guidance. User choices and this skill's interview/preview gates take precedence over conflicting defaults.

For focused finishing work, an installed `anti-ui-slop` skill may provide a `reference/polish.md` module about design-system alignment, information hierarchy, flows, spacing, media treatment, and complete interaction states. Locate it from that installed skill's actual directory, and skip it if unavailable. A clean automated check does not prove visual quality. This is a selective reference, not a requirement to run its separate workflow or connect an external service. User restrictions on browser review and the agreed media policy remain in force.

## UI/UX Pro Max

Optional source: the installed `ui-ux-pro-max` skill, if available in the agent's skill catalog.

Useful strengths:
- Product/style reasoning and searchable palettes, typography, navigation, forms, interaction, and accessibility guidance.
- A coherent design specification with a shared master and explicit page variations.
- Prioritizing accessibility and interaction before decorative choices.

For an actual project with a sufficiently complete brief, resolve the installed skill directory and use its `scripts/search.py` with a query combining product, audience, style, and density. Begin with `--design-system`; supplement with a focused `--domain` query only for an unresolved choice. If implementation guidance is needed, detect the actual stack rather than assuming one. Consult `references/quick-reference.md` for focused UX rules and `references/pro-rules.md` for relevant app/mobile checks.

Do not run a generic design-system search merely while editing this skill. Do not overwrite existing approved master decisions with generated suggestions. Use absolute resolved script paths; do not assume the current project contains the script. Empty results are empty results, not supporting evidence. A local database does not establish what is popular today.

## Frontend Design

Optional source: the installed `frontend-design` skill, if available in the agent's skill catalog.

Useful strengths:
- Derive the visual language from the actual subject, materials, audience, and content.
- Use deliberate typography and a compact palette with clear roles.
- Review a short design plan against the brief before building.
- Give the page one memorable quality while keeping surrounding content disciplined.
- Use plain, functional interface copy, consistent action names, and actionable empty/error states.

Do not turn its observations about common generated designs into universal bans on a user's chosen colors or typeface. An intentional user preference takes precedence.

## Design Taste Frontend

Optional source: the installed `design-taste-frontend` skill, if available in the agent's skill catalog.

Useful strengths:
- Declare the design interpretation and distinguish a new build, brand-preserving redesign, and overhaul.
- Calibrate visual expressiveness, motion, and density to context.
- Maintain consistent palette, shape, theme, navigation, and component states.
- Distinguish genuine design systems from aesthetics and web approximations.
- Audit the complete composition, relevant visual assets, realistic content, responsive behavior, and interaction states.

Use its landing-page and portfolio advice where appropriate. Do not impose marketing-page layout rules on a dashboard or complex workflow. Do not inherit arbitrary defaults for React, animation intensity, both color modes, font bans, forced imagery, or section counts. Its strict aesthetic rules are review prompts whose suitability depends on the user's brief. Its image-first, browser, Lighthouse, installation, or test instructions do not override user restrictions or the chosen preview route. Never adopt advice to invent natural-looking metrics or business facts.

## Current research starting points

These links are starting points, not sources already inspected for a particular project. Open and verify the relevant pages when actually using them; record the access date and observation in the project's analysis.

- The user's own references and real competing/comparable product pages: inspect the relevant task or page, not just a screenshot gallery.
- [Awwwards](https://www.awwwards.com/) and [Godly](https://godly.website/): visual composition and contemporary examples; gallery presence does not prove usability or suitability.
- [Material Design](https://m3.material.io/): product patterns and design-system guidance.
- [Fluent](https://fluent2.microsoft.design/): Microsoft design-system guidance.
- [Carbon](https://carbondesignsystem.com/): enterprise interface guidance.
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/): platform guidance; distinguish native platform materials from web approximations.
- [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/): accessibility guidance; verify the relevant published version when citing formal requirements.
- The selected framework/library's official documentation: verify current APIs and technical recommendations when needed.

Prefer a small, relevant evidence set over collecting many links. For each reference, record what was observed, what will be adapted, and what will not fit this audience. Never claim a source was inspected if only its name or search snippet was available.
