# Project deliverables

Reuse suitable existing project documents. Otherwise create the following under `docs/ui-design/`. Write them in the user's language unless the repository has a documented language convention. Keep them specific, accurate, and proportional to scope; avoid empty boilerplate. Separate confirmed facts, assumptions, proposed behavior, implemented behavior, and verified behavior.

## project-analysis.md (always)

- Project concept, audience, problem, primary goal, scope, and success criteria
- User choices: style, font, palette, identity, themes, preview route, documentation scope
- Media policy and scope of delegation, including image-free sections and selected alternatives
- Existing experience and constraints, if applicable
- Needs, primary journeys, page inventory, navigation, and content gaps
- Main-page section map: section, user need, content, action, required assets/data, mobile treatment
- Current references: URL, access date, observation, adaptation, and any research limitation
- Rationale for added, removed, or reorganized sections
- Assumptions, dependencies, unresolved decisions, and scope boundaries

Analysis is required even for a one-page project. A list of headings without reasoning is not a complete analysis.

## design-spec.md (always)

- One-sentence design interpretation
- Identity: visual personality, logo/wordmark treatment, voice, imagery, and icon style
- Chosen aesthetic and, if applicable, established or custom design system
- Typography: actual families, roles, scale, weights, line height, script coverage, fallbacks, asset/license requirements
- Named palette values and semantic roles, theme behavior, and contrast considerations
- Spacing, grid, density, radii, surfaces, depth, and responsive rules
- Components and relevant interactive states
- Motion rationale and reduced-motion behavior
- Asset inventory and any clearly identified sample assets
- Asset plan: section, visual purpose, approved source/replacement, actual file or URL, relevant usage conditions, fallback, and pending decisions; never invent user approval
- Approved preview file/version, approval evidence from the conversation, and changes requested

If approval is pending, state that explicitly. Never invent an approval timestamp or assume silence is acceptance.

## technical-notes.md (always)

Describe this actual project, not a preferred generic stack. Cover applicable topics:

- Observed framework/platform and relevant existing conventions
- Files, routes, components, styles/tokens, and asset locations affected by the work
- Component responsibilities and reusable patterns
- State and interaction behavior, forms and validation, navigation, search/filter/cart logic as relevant
- Data/API integration points, loading/error handling, and dependencies; clearly mark mocks or unavailable services
- Responsive, RTL/localization, accessibility, and theme implementation
- Font/image handling and performance considerations without claiming unmeasured results
- Practical maintenance or extension notes, and existing run/verification instructions if known
- Checks actually performed, limitations, and remaining work

Use concrete file references where possible. For a plain HTML prototype, explain its sections, styles, interactions, sample data, and limits; do not invent server architecture. For a preview awaiting approval, document the proposed approach as proposed and update after implementation. Do not run production builds merely to populate this document.

## pages/<page-name>.md (only when requested)

For every page in the agreed analysis scope:

- Purpose, audience, entry points, and primary/secondary actions
- Content hierarchy and section structure
- Main journey, alternatives, validation, loading, empty, error, success, and permission states as applicable
- Navigation to/from other pages
- Data, assets, integrations, and reusable components
- Responsive/RTL/accessibility behavior
- Rationale, dependencies, acceptance conditions, assumptions, and open questions

Do not add detailed page reports outside the requested scope merely to produce more documents.

## Previews (conditional)

Use `design-previews/` with descriptive filenames such as `design-system.html`, `home-preview.html`, or a returned concept-image filename. Keep revisions traceable if a previous version has already been approved. A preview cannot be counted as the implemented project unless the user requested only a standalone prototype.

## Structure and skeleton (when requested)

Deliver `docs/ui-design/page-structure.md` and `design-previews/wireframe.html` by default. Read [media-and-structure.md](media-and-structure.md) for details.

The document contains the requested page tree, navigation, section order, hierarchy, goals, actions, content/asset needs, and desktop/mobile layout decisions. The HTML is a lightweight, neutral wireframe with meaningful section labels and representative content lengths. Clearly label any provisional media blocks. It should make the composition understandable before final styling, not imply that empty placeholder blocks are a finished design.

Deliver only the structure when that is the requested scope. If the user asks for a code skeleton, provide a useful semantic scaffold in the requested format without silently creating a new framework or application. Record whether the wireframe is for approval or simply an export of the current structure.

## Final report (always, concise)

Report:
1. What the project needed and the design direction chosen
2. Sections/pages completed and important UX improvements
3. Key decisions drawn from references and confirmed user preferences
4. Checks actually performed and material limitations or missing integrations/assets
5. Clickable links to the interface, requested previews, overall analysis, design specification, technical notes, and optional page reports
6. When relevant, media decisions and replacements, the structure/wireframe exports, and specific generic-design or usability issues corrected

Do not claim full functionality or production readiness based only on a visual concept, static file inspection, or generated image. State prototype limits in the report; keep development explanations out of the product's normal user flow.
