# UI Studio

A reusable agent skill for understanding, designing, and completing project-specific interfaces. UI Studio adapts to the product and its audience, researches relevant references, then redesigns or builds the agreed scope and documents the result.

[راهنمای فارسی](README.fa.md)

A standalone Persian master prompt is available in [PROMPT.fa.md](PROMPT.fa.md).

## Install

Install the published skill from this repository:

```bash
npx skills add Sizzlesina/ui-studio --skill ui-studio
```

To install across projects:

```bash
npx skills add Sizzlesina/ui-studio --skill ui-studio -g
```

The CLI lets you choose supported agents. Node.js and npm are needed to run `npx`; see the [official CLI documentation](https://github.com/vercel-labs/skills) for current requirements and options. UI Studio itself has no package dependencies or install scripts.

## Use

In an agent that supports explicit skill mentions, invoke `$ui-studio`. Otherwise select UI Studio through that agent's skill interface or ask it to use the installed skill.

Example requests:

```text
Use ui-studio to redesign our car-accessories storefront.
Ask me about the project and design style first. I want to review
the page structure and an HTML design-system preview before implementation.
```

Redesign an existing product:

```text
Use ui-studio to redesign the current product experience. Audit the in-scope
pages and main user journeys first; show the evidence-backed weaknesses and
what you recommend keeping, improving, replacing, or adding. Preserve working
flows and useful brand identity. Research relevant competitors and credible
UX sources, complete every page and component in scope, and review the full
result on desktop and mobile. Do not leave demo labels, placeholders, or dead
controls in a finished concept.
```

```text
Use ui-studio for a clinic appointment website. I have an existing logo
and font. Help me choose colors and complete the homepage. Ask before
using images and include technical documentation.
```

```text
Use ui-studio to improve our inventory dashboard. Keep its working flows.
Use no photography; propose useful alternatives. Deliver only the structure
and HTML wireframe first.
```

## What it does

UI Studio follows the project from discovery to handoff:

1. **Understand the project.** Establish the product, audience, primary tasks, scope, language, visual preferences, brand assets, and media choices. Reuse answers already given instead of repeating questions.
2. **Research with a purpose.** Review relevant UX/design sources and actual competitors when browsing is available. Turn observations into design decisions; do not copy another product's identity or claim that an undated style is a current trend.
3. **Set the direction.** Define visual personality, color roles, typography, layout density, imagery, navigation, interaction language, responsive behavior, accessibility, and motion around the product.
4. **Complete the agreed scope.** Build purposeful sections and complete visible components, including relevant interaction states and mobile layouts. For a redesign, audit the current experience and preserve essential flows and useful identity.
5. **Review and document.** Inspect the full result when permitted, fix high-impact gaps, and report the work, assumptions, verification, and limits.

### Visual quality standard

Minimalism is not the default. Match visual and content density to the product, audience, and requested style. A complete storefront or product page should feel finished and useful—not like an empty demo or concept board. Never add filler, arbitrary decoration, or fabricated business claims just to make a page look fuller. Check whole-page rhythm, contrast, meaningful content coverage, component completeness, and responsive behavior before delivery.

When a new design system is recommended, UI Studio provides an HTML sample for approval before applying it unless the user explicitly waives that step. A requested wireframe or page preview has its own approval boundary; see `SKILL.md` for the full rules.

## What is included

```text
SKILL.md
PROMPT.fa.md
references/
  style-conversation.md
  design-sources.md
  media-and-structure.md
  deliverables.md
```

The reference files are bundled with the skill. UI/UX Pro Max, Frontend Design, Design Taste Frontend, and Anti UI Slop are optional sources of additional guidance if already installed. Their files and tooling are not bundled or installed automatically. No subscription or external design service is required by UI Studio.

## Capabilities and limits

This repository contains instructions, not a standalone design application. The host agent supplies filesystem access, implementation tools, browsing, and optional image generation. UI Studio requires honest disclosure when a capability or verification step is unavailable. It respects user and project restrictions on builds, servers, browser checks, and expensive workflows.

Design quality remains a matter of fit and judgment. Static checks cannot establish visual quality, and generated mockups do not prove working application behavior.

## Publish your copy

1. Keep `SKILL.md` at the root of the `Sizzlesina/ui-studio` repository and include the `references/` folder.
2. Push the updated files to GitHub.
3. Share the install command above. No npm package publication is required.

No npm package publication is required. The [Skills FAQ](https://www.skills.sh/docs/faq) explains discovery and leaderboard listing through CLI installation telemetry. This local folder has not been published by creating these files.

## License

[MIT](LICENSE) for the material distributed in this repository. Optional third-party skills, tools, fonts, and media retain their own terms and are not redistributed here.
