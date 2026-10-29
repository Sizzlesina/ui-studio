# UI Studio

A reusable agent skill for designing complete, project-specific interfaces through a short conversation, relevant references, visual direction, optional previews, and implementation.

[راهنمای فارسی](README.fa.md)

## Install

After this repository is published on GitHub, replace `YOUR_GITHUB_USERNAME` with its owner:

```bash
npx skills add YOUR_GITHUB_USERNAME/ui-studio --skill ui-studio
```

To install across projects:

```bash
npx skills add YOUR_GITHUB_USERNAME/ui-studio --skill ui-studio -g
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

- Asks about the project, audience, visual style, fonts, colors, and identity.
- Explains styles and generates concept images when requested and supported.
- Uses a small set of relevant current references when browsing is available.
- Plans a complete page around user needs, with purposeful sections and working interactions.
- Asks before selecting a media route: supplied, sourced, generated, external, or an alternative element.
- Can deliver an exportable page outline and responsive HTML wireframe.
- Presents a newly recommended design system in HTML for approval before applying it, unless the user explicitly waives that step.
- Reviews common generic-design patterns, accessibility, responsive behavior, and interaction completeness.
- Produces overall analysis, design specifications, technical notes, and a concise final report. Detailed page analysis is optional.

## What is included

```text
SKILL.md
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

1. Create a public GitHub repository named `ui-studio`.
2. Upload this folder's **contents** to the repository root, so `SKILL.md` is at the root.
3. Replace `YOUR_GITHUB_USERNAME` in both README files with the repository owner.
4. Share the install command above.

No npm package publication is required. The [Skills FAQ](https://www.skills.sh/docs/faq) explains discovery and leaderboard listing through CLI installation telemetry. This local folder has not been published by creating these files.

## License

[MIT](LICENSE) for the material distributed in this repository. Optional third-party skills, tools, fonts, and media retain their own terms and are not redistributed here.
