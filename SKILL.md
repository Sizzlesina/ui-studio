---
name: ui-studio
license: MIT
description: Guide project-specific UI/UX design, complete-page work, or redesign of existing websites, storefronts, apps, and dashboards. First understand the product and style, then research relevant sources and competitors, audit existing experiences when redesigning, shape a distinctive visual system, complete all in-scope pages and components, and review the result before delivery. Explain styles and generate requested concept images. Present any newly recommended design system in HTML for approval before applying it.
---

# UI Studio

Build a complete experience around the user's project, audience, and chosen direction. Conduct a short design conversation, investigate appropriate references, complete the analysis, then apply the design within the agreed scope. Deliver the actual requested interface and project-specific documentation.

Use the user's language for questions, explanations, and reports. Keep technical details in the technical documentation unless they affect a decision the user needs to make.

## Operating rules

- Follow current user instructions and project rules over borrowed defaults from other skills.
- A request to edit this skill means edit its instructions. Do not start the project interview or redesign a previous demo while editing the skill.
- Start fresh for each new project. Do not assume a previous project's industry, language, brand, fonts, or palette applies.
- Treat answers already provided for the current project as completed interview questions. Record them; do not repeatedly ask for the same information.
- Ask required questions before committing to a design. Silence is not a preference or approval. An explicit “you choose” delegates the decision.
- Ask in short rounds, usually one to three related questions. Avoid a long form or unnecessary approvals.
- Preserve essential content and behavior in redesigns. Complete missing homepage sections within the agreed scope; do not silently expand into an entire application.
- Follow local restrictions on builds, servers, browser testing, subagents, and expensive research. This skill does not authorize those activities by itself.

## 1. Ask what the project is

At the start of a new project, ask for its subject and primary purpose before selecting an aesthetic. If those are already explicit in the current request, acknowledge them and move to style selection.

Example opening in Persian:

> موضوع پروژه چیه و کاربر با ورود به سایت یا اپ باید بتونه چه کاری انجام بده؟

Establish whether this is a new project, a redesign preserving its brand, or a visual overhaul. Use available project material to understand the existing experience, but do not silently substitute workspace context for the user's project choice.

## 2. Ask for the design style and help the user choose

Ask which visual direction the user wants. Offer a short, relevant selection with an “offer your recommendation” choice. Possible families include minimalism, maximalism, glassmorphism, editorial, neo-brutalism, refined luxury, playful illustration, or restrained product UI. These are examples, not a mandatory menu or a universal ranking.

Read [references/style-conversation.md](references/style-conversation.md) when explaining or comparing styles.

- Explain any requested style in plain language: how it looks and feels, where it works, and its usability tradeoffs.
- For an unfamiliar or ambiguous label, ask what the user means. For example, do not invent a definition of “اکسترالیسم”; ask whether they mean maximalism, an experimental style, or a specific reference.
- Recommend two or three suitable directions if the user has no preference. Explain the fit to their audience and goal rather than calling one universally best.
- If the user asks to see an image, generate a relevant concept image using the available image-generation capability and its instructions. Show the image; a text description is not a substitute. Label it as a concept, not a screenshot of an implemented page.
- For comparisons, use the same project content across styles so the difference is meaningful.
- Answer follow-up questions and retain confirmed choices. Explain concerns with readability or usability and offer an adjustment that preserves the requested character.

## 3. Complete the brief in short rounds

Ask only questions whose answers change the design or scope. Cover the following, using existing answers where available:

| Topic | What to establish |
| --- | --- |
| Audience and goal | Who uses it, the main task or conversion, and key uncertainties they need resolved |
| Scope | Main page, selected pages, or whole product; essential sections and user flows |
| Language and devices | Language, RTL/LTR, mobile priorities, and any special accessibility needs |
| References | Sites, images, competitors, or styles they like or dislike |
| Font | Whether they have a chosen font; otherwise propose a suitable option and a fallback |
| Colors | Whether there is a required palette; otherwise choose and explain a coherent palette |
| Visual identity | Whether they have a logo, brand guide, assets, or a recognizable identity to preserve |
| Images and replacements | Whether to use user-provided assets, agent-sourced or generated images, external image URLs, a non-image element, or no imagery; ask before choosing the route |
| Structure output | Whether they want a separate page/section blueprint and HTML wireframe, and whether to review it before visual implementation |
| Presentation | Whether they want an HTML page preview, a generated concept image, both, or direct implementation |
| Design-system option | Whether to keep an existing system, use a specified one, or receive a recommended system with an HTML sample |
| Documentation | Overall analysis and technical documentation are included; ask whether detailed page-by-page analysis is also wanted |

When brand assets exist, invite the user to provide the files or links and use them. Request uploads in a normal chat message, not through a text-only question tool. If there is no visual identity, develop one appropriate to the concept: visual personality, wordmark/logo direction, colors, typography, iconography, imagery, and voice. Distinguish a proposed identity from assets actually created.

Respect a selected font when it is usable. If unavailable, unlicensed for the intended use, or missing the required script, explain and propose a suitable alternative; do not silently substitute it. If no font is chosen, recommend one or two families with roles and script coverage. For Persian, account for Persian glyphs, numerals, mixed-direction text, and natural spacing.

Respect selected brand colors and choose accessible supporting tones. If no palette is given, select it based on the subject and selected style, and document semantic roles. Avoid a new color scheme on every section.

End discovery with a concise interpretation: product, audience, primary goal, selected style, brand decisions, scope, and preview route. Ask only about unresolved decisions; do not introduce an extra approval step when direct implementation was chosen.

### Agree on imagery and alternatives

Read [references/media-and-structure.md](references/media-and-structure.md) when planning assets or delivering a skeleton.

Before sourcing, generating, embedding, or replacing a planned image, explain its purpose and ask which route the user wants. Group similar needs into one short question. Offer supplied images, agent-selected images, externally linked images, generated visuals, another element, or a different section composition. Do not choose stock photography, an external URL, or a Canvas effect silently.

A decision may apply to the whole project or specified sections. Record that scope and honor explicit delegation without asking about every asset again. Permission to browse design references is not permission to embed those images. Permission to generate a style-explanation image is not permission to add generated assets throughout the site.

If the user rejects images, ask which alternative they prefer or offer two useful alternatives and let them delegate the choice. Possibilities include stronger typography, a meaningful diagram, a real interactive component, an HTML Canvas composition, a comparison, or a different section. Preserve the section's purpose; do not leave a large empty media slot or replace it with arbitrary decoration. Do not force imagery through another skill's defaults.

While required images or a media decision are pending, continue independent analysis and structure work. Keep provisional slots clearly identified in previews and the asset plan; do not represent them as finished product content.

## 4. Ground the proposal in current references

Read [references/design-sources.md](references/design-sources.md) for reusable guidance and source starting points.

- For a typical website or storefront, inspect two to four credible UX/design sources and two to four real competitors in the target market. Use fewer only when the niche has few relevant examples, and explain the limitation. Prioritize references that answer a concrete unresolved design question; do not turn research into an inspiration dump.
- For trend requests, include at least one recent, dated source and inspect its expertise or method. Treat usability evidence and aesthetic trend signals separately. Do not call a style current based only on memory, an undated gallery, or a local pattern database.
- Identify direct competitors for the audience and market; inspect their actual pages and mobile presentation when available. Search snippets and generic inspiration collections are not competitor analysis. If a site is blocked or partially readable, report that limitation and choose another useful source where possible.
- Compare relevant patterns: discovery and navigation, primary actions, information architecture, search/filtering, product/content presentation, trust cues, imagery, responsive behavior, and key states. State which patterns informed the design and which were avoided. A competitor using a pattern does not prove it works; never copy its branding, wording, assets, or distinctive page composition.
- Record each source's direct URL, access date, observable evidence, and design implication. Separate facts from interpretation and cite sources near claims in the analysis. Before styling, summarize how the findings changed or validated the direction.
- Verify what each source actually shows. Record its URL, access date, relevant observation, and how that observation informs this project. Separate observation from your interpretation.
- Use trends selectively. Do not claim something is a current trend merely because it appears in training knowledge, a local database, or an undated gallery.
- If browsing is unavailable or prohibited, disclose that current trends could not be verified and work from the user's references and established principles.
- Adapt useful hierarchy, interaction, typography, and composition patterns. Do not copy a whole site or invent testimonials, endorsements, compatibility claims, or business metrics.
- Use the installed UI/UX Pro Max database when helpful for product patterns, styles, palettes, typography, and UX rules. Its results are design suggestions, not approval or proof of current popularity.

This research should answer concrete design questions. Do not turn a small interface task into an open-ended research project.

## 5. Analyze the experience and complete its structure

Always prepare an overall project analysis before implementation and keep it aligned with the finished work. Read [references/deliverables.md](references/deliverables.md) for the documentation structure.

Identify goals, audience, primary journeys, page relationships, content gaps, and important interaction states. Distinguish observed facts, assumptions, and proposed additions. For redesigns, identify what should remain, improve, or be replaced.

Build the main page around the questions and tasks its users bring. A homepage should support orientation, discovery, evaluation, trust, and the next useful action as applicable. Determine the necessary sections from those needs. Do not stop at a hero and a row of cards, or add filler just to make the page longer.

Create a section map with each section's purpose, key content, action or next step, asset/data needs, and mobile treatment. Add missing sections and reorganize existing sections where needed within scope. Avoid repeated messages and repeated layouts that make unrelated content feel identical.

When the user asks for the structure, skeleton, or wireframe, deliver an actual exportable artifact. Default to a readable `page-structure.md` plus a simple `wireframe.html` showing the requested scope, section order, hierarchy, navigation, main actions, and mobile layout. Keep it independent of final colors and imagery. If the request is only for a skeleton, stop at that deliverable. If it is a preview for approval, wait before applying the visual design. An additional structure export does not by itself create a new approval gate.

When the user asks for a complete product, website, or storefront, do not mistake a polished hero or a clickable mockup for a complete experience. Confirm the intended scope, then provide every in-scope page or fully complete page requested, with a coherent page map, usable navigation, meaningful content, complete section structure, relevant product/content assortment, finished footer, and the interaction states needed for the primary journeys. Do not stop at a skeleton or one screen if the agreed scope is the whole product. Do not silently expand a one-page request into an application.

Avoid visible scaffold cues in a polished concept: “sample/demo/coming soon” labels, TODOs, filler copy, empty section shells, inactive controls, or repeated caveats. If actual inventory, contact details, policies, compatibility, testimonials, or business metrics are unknown, use a clearly reasoned proposed content model without making those claims appear verified. Explain assumptions once in the accompanying project notes; never fabricate guarantees or operational details to make a screen feel complete.

For product apps and dashboards, prioritize useful information, common tasks, navigation, and states instead of importing a marketing-page structure. For storefronts, distinguish real product images from contextual photography; never use a car photograph as if it were a photo of a phone holder. Compatibility controls must not claim verified compatibility without supporting data.

If detailed page analysis was requested, cover every page in the agreed scope, including its goal, entry/exit points, sections, interactions, states, dependencies, and responsive behavior. Otherwise include a concise page inventory and primary journeys in the overall analysis.

## 5A. Redesign an existing project

Use this route whenever the user asks to redesign, refresh, modernize, improve, or complete an existing interface. Audit what exists before changing it; do not approach a redesign as an unrelated blank-page concept.

1. **Set the redesign boundary.** Establish whether the user wants a focused page/flow improvement, a visual refresh that preserves the identity, or a broader experience redesign. Use the current request and prior answers to infer it where clear; ask only if the choice would materially change scope.
2. **Understand the current experience.** Review the requested pages and their real content, visual hierarchy, navigation, available brand assets, components, responsive presentation, and key states. Identify the main user journeys and friction points. Separate observable problems from taste preferences and assumptions.
3. **Create a concise before/change map.** For each in-scope page or component, state what to keep, improve, replace, add, or remove, and why. Preserve valuable identity, content, accessibility, and behavior. Do not delete a flow merely because it is visually inconvenient, and do not redesign unrelated areas.
4. **Close completeness gaps inside scope.** Identify missing sections, disconnected navigation, incomplete component states, unhelpful content, dead actions, category gaps, and mobile problems. Add the sections and states necessary to complete the user's requested journey; do not add filler to increase page length.
5. **Apply one coherent direction across the scope.** Preserve or intentionally evolve the existing design system. When multiple pages are in scope, keep shared navigation, type, color roles, spacing, imagery, component states, and interaction language coherent across all of them. Do not make the first screen polished while leaving the rest visually or structurally unfinished.
6. **Compare the result to the baseline.** Review every in-scope page and the primary user journeys after redesign. Confirm that the new hierarchy solves the identified problems and that essential actions, content, and states remain available. Report what was retained, changed, newly completed, and any remaining limitation.

Do not claim that a redesign is complete based on a hero or screenshot alone. Completion means the full agreed scope has been redesigned, all visible components are considered, and the resulting experience supports the intended tasks at the relevant screen sizes.

## 6. Define the identity and design system

Translate the brief into an explicit, coherent design specification:

- Visual personality and the memorable quality specific to this project
- Color roles, exact values, contrast, and feedback colors
- Font families, roles, scale, weights, line lengths, and script support
- Spacing, layout density, alignment, grid, and responsive behavior
- Component appearance, borders, radii, depth, and interaction states
- Icons, imagery, illustration, and asset requirements
- Theme choice, purposeful motion, and reduced-motion alternatives
- Voice, labels, action naming, and content principles

Choose layout expressiveness, motion intensity, and information density from the brief. These can use the three dials from design-taste-frontend, but do not impose its numerical defaults or scope restrictions on every project.

Distinguish an aesthetic such as glassmorphism from an established design system such as Material or Carbon. Do not claim that a custom preview is an official implementation. Choose an existing system only when it fits the project; do not silently migrate its framework or mix competing systems.

### Make the art direction recognizable

Do not mistake a competent layout, fashionable palette, or impressive hero image for a strong direction. Define at least two product-specific visual or interaction anchors beyond the logo and colors—for example a distinctive editorial composition, useful selection interaction, subject-based graphic motif, photography treatment, or type/layout relationship. Give each page section a distinct purpose and vary the pace and density; do not repeat the same photo, card grid, split panel, eyebrow label, or promo banner without a content reason. Review the first viewport at normal size and the full page as a reduced overview: the first should quickly explain the product and next action, while the overview should have clear rhythm and memorable moments. If the work reads as a generic “hero + accent color + product cards” shell, strengthen the concept before adding polish.

### Prevent accidental minimalism and underfilled pages

Minimalism is a deliberate style choice, never the default shortcut. Derive visual and information density from the product, audience, scope, and selected style. A request for a complete store, homepage, or product experience usually needs enough real, purposeful content to support discovery, evaluation, trust, and action; do not make it feel like a sparse concept board or demo merely to keep the layout clean.

Before implementation, state the intended density and explain it through the content model. For a storefront, consider the actual buying journey: category discovery, a useful assortment, product comparison, fitment or selection help when relevant, purchase actions, decision-support content, and service/policy information when known. Include only sections that serve this project; when facts are unknown, use clearly proposed content without inventing business claims. For other products, fill the scope with the tasks, information, and states users actually need.

At full-page overview size, challenge these warning signs: large unused areas without a compositional reason; many low-contrast surfaces that merge together; oversized gaps between small amounts of content; thin outlines and delicate icons doing all the visual work; too few meaningful sections or items for the agreed scope; identical card grids repeated to simulate completeness; or a page that still reads as a wireframe/demo. If present, improve the content hierarchy, section rhythm, useful assortment, color contrast, image scale, and layout variation. Do not solve emptiness with arbitrary decoration, invented claims, or filler text. Respect a user-selected minimalist direction, but make that minimalism intentional and complete rather than empty.

## 7. Deliver requested previews and honor approval

Apply this decision table before modifying the actual project interface:

| Chosen route | Required action |
| --- | --- |
| Newly recommended design system | Create a concrete HTML design-system preview, present it, and wait for explicit approval before applying that system |
| User requests an HTML page preview before implementation | Create the requested page preview, present it, and wait for approval |
| User requests a structural wireframe for approval before visual design | Deliver the blueprint and wireframe, then wait for approval before proceeding to the visual design |
| User requests a proposed-appearance image before implementation | Generate and show the image, then obtain approval of that direction before implementation |
| Existing/specified direction and no preview requested | Once discovery is complete, proceed with implementation |
| User explicitly delegates all decisions and waives previews/approval | Record the delegation and proceed; do not ask for an already waived step |

An image requested just to explain a style is educational; it does not automatically approve that style or the finished design. A generated image does not replace the HTML preview required for a newly recommended design system.

The general “no page preview” choice does not silently waive the design-system preview when a new system is being recommended. Explain that specific gate and show the concrete HTML. Honor an explicit user override of the gate.

Make previews useful and easy to review:

- A design-system HTML preview includes the palette, real font samples, hierarchy, spacing/shape examples, buttons, forms, relevant states, and at least one realistic composition using the project's content.
- A page HTML preview includes the full proposed section structure and representative desktop/mobile behavior, not merely a palette sheet or hero.
- Use local fonts/assets where practical, explain any external dependencies, and avoid broken imagery. Do not claim a requested font is present if it failed to load.
- Provide a clickable file and show it with available presentation tools where permitted. Do not run a server or browser check if project rules prohibit it.
- Record the approved artifact/version and decisions. If revisions are requested, revise the preview and seek approval of the changed direction. During implementation, reproduce the approved structure, type, palette, imagery direction, and states rather than inventing a different design.
- Continue research and documentation while approval is pending, but do not apply an unapproved proposal to the actual interface. Approval of one preview does not approve a different variant.

## 8. Apply the complete design

Implement the agreed interface and complete the agreed main-page sections. Use the project's actual environment, established behavior, content, and constraints. Do not deliver a report or mockup as a substitute when implementation was requested; a preview-only request ends with the preview.

Complete the visible components, not only their page-level arrangement. For every component used in the agreed scope, define its content, hierarchy, responsive layout, visual variants, and relevant interaction states. Check shared components such as navigation, search, filters, product/content cards, forms, tabs, accordions, dialogs, notices, and footer when present. A component is unfinished if it has a visible control with no useful action, a missing state needed by its flow, placeholder content, broken mobile layout, or styling that conflicts with the approved system. Reuse components where that improves consistency, but vary composition when sections have different jobs.

Use these quality principles throughout:

- Give the main action and content a clear hierarchy. Use grouping and whitespace purposefully.
- Make typography and composition specific to the subject. Spend visual emphasis where it matters; avoid decorative labels and repetitive boxes.
- Keep action labels consistent and connect every visible interactive control to its stated behavior. Do not simulate success for a search, filter, cart, or form that did not perform its action. Identify prototype limitations clearly in the delivery report.
- Provide relevant loading, empty, error, success, selected, disabled, hover, and focus states. Use visible form labels and actionable error messages.
- Target WCAG AA contrast: 4.5:1 for normal text, 3:1 for large text, and appropriate 3:1 contrast for essential control boundaries and focus indicators. Provide keyboard use and accessible names. Aim for touch targets of at least 44 by 44 CSS pixels.
- Design for narrow screens, text enlargement, mixed content lengths, and the project's language/direction. Avoid clipping and unintended horizontal overflow.
- Use motion to communicate feedback, hierarchy, or a transition. Respect reduced motion. Glass effects need readable solid fallbacks.
- Use coherent icons and relevant imagery. Prefer existing accurate product assets; generated or illustrative assets must not misrepresent real merchandise.
- Use the agreed media route for each section. A no-image layout can be complete and distinctive; Canvas, charts, diagrams, or interactive elements must serve the content and remain accessible.
- Preserve brand recognition, essential journeys, accessibility gains, integrations, and valid content during redesigns. Do not quietly change legal claims or consent behavior.

### Review for generic UI and unfinished experience

Before implementation, challenge the proposed composition: could changing only the name and logo make this page fit an unrelated business? If so, revise its content hierarchy, visuals, and key interactions around this project's actual needs. Carry that direction through all sections, rather than adding superficial decorative differences.

Review once at the end using the lowest-cost sufficient checks allowed by the user. Look for repeated section patterns without a content reason, uniform card containers around everything, decorative badges/eyebrows, stock imagery unrelated to the content, arbitrary effects, vague copy, and controls with no useful behavior. These are contextual warning signs, not universal bans on a user's chosen style. Preserve familiar patterns when they help the task.

Resolve observable issues in hierarchy, spacing, legibility, media relevance, consistency, mobile layout, and interaction completeness. If rendered review is permitted, inspect the whole requested scope and key interactions. If it is not, perform a static review and state its limits. Do not manufacture a design score or guarantee that subjective taste has been proven. Report concrete issues corrected and any remaining gaps. Never claim a visual/browser review, successful test, or performance measurement that was not performed.

Use a concise finish gate on the complete result: mark product specificity, task hierarchy, content completeness/density, composition rhythm, component completeness, visual craft, and responsive quality as pass or needs revision. Specifically ask whether the full page feels underfilled or like a demo at overview size, and whether all visible components and their key states are complete. Fix high-impact failures before delivery. Treat this as a qualitative review, not a numeric score. When the user asks for critique, state the strongest evidence-backed weaknesses before proposing or applying corrections.

## 9. Finish the documents and report

Use the templates in [references/deliverables.md](references/deliverables.md). At minimum deliver:

1. Overall project analysis, including page inventory, journeys, section rationale, assumptions, and references.
2. Design specification/visual identity with the final decisions and approval record where applicable.
3. Project-specific technical documentation that describes what actually exists and distinguishes proposals from implemented behavior.
4. The requested interface and any requested/required previews.
5. Detailed page-by-page analysis only when requested.
6. A separate structure blueprint and HTML wireframe when requested, plus an asset plan recording the user's media choices and unresolved needs.

Update existing documentation when appropriate; otherwise use a small project-local `docs/ui-design/` directory. Keep previews in a project-local `design-previews/` directory. Avoid duplicate competing documents or writing project data into the skill's own folder.

End with a concise report in the user's language: what you understood, which sections and UX you completed, why the design fits, what was checked, material remaining gaps, and clickable links to the interface, previews, analysis, and technical documents.
