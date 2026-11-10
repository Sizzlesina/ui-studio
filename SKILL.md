---
name: ui-studio
license: MIT
description: Guide project-specific UI/UX design, complete-page work, or redesign of existing websites, storefronts, apps, and dashboards. Adapts flexibly to task scope: jumps directly to high-quality implementation for direct requests, or conducts a guided design workflow when requested. Ensures high craft, accessibility, responsiveness, and complete states without unnecessary token bloat or slow multi-step bottlenecks.
---

# UI Studio

UI Studio designs, refines, and builds complete, production-grade user interfaces tailored to each project's purpose and audience. It scales seamlessly from quick component styling to full product architectures.

Use the user's language for questions, explanations, and code comments.

---

## Operating Modes (Adaptive Execution)

To ensure fast execution and avoid model timeouts, rate limits, or context bloat, always determine the execution mode first:

### 1. Direct Implementation Mode (Default for code & UI tasks)
- **When to use:** The user asks to build, modify, restyle, fix, or implement a specific page, screen, component, or layout (e.g., "این صفحه رو طراحی کن", "کامپوننت کارت‌ها رو بازطراحی کن").
- **Behavior:**
  - **Do NOT** conduct a lengthy multi-round interview.
  - **Do NOT** perform automatic web research, competitor scraping, or external queries unless explicitly requested.
  - **Do NOT** generate separate documentation files (`project-analysis.md`, `design-spec.md`, etc.) unless requested.
  - **Action:** Infer sensible, modern defaults (clean typography, coherent palette, accessible contrast, responsive layout) and implement the code directly in the target files. Keep explanations brief.

### 2. Guided Design Studio Mode (Only when explicitly requested)
- **When to use:** The user explicitly asks for end-to-end design consulting, style discovery, research, or architecture (e.g., "مراحل طراحی رو از صفر با من پیش ببر", "برام تحقیق کن و استایل پیشنهاد بده", "اول وایرفریم بده تا تایید کنم").
- **Behavior:** Follow the guided steps below in short, focused rounds (maximum 1-2 questions at a time).

---

## Core Guidelines & Quality Standards

Regardless of mode, always enforce high UI/UX craft:

### 1. Art Direction & Visual Cohesion
- Avoid generic "hero + 3 identical cards" shells. Give each interface a distinct, project-specific visual rhythm.
- Define a clear visual hierarchy: primary action, key content, and secondary controls.
- Prevent accidental minimalism / underfilled pages: ensure complete real-world content structure (actions, navigation, footer, relevant empty/error states) rather than an empty demo mockup.
- Never invent misleading operational claims, fake guarantees, or non-existent business facts in user-facing copy.

### 2. Component & Interaction Completeness
- Provide all necessary interactive states: default, hover, focus-visible, active, disabled, loading, empty, and error.
- Connect visible controls to meaningful behavior or clearly mark prototype limits.
- Ensure touch targets are at least 44×44 CSS pixels on mobile.
- Enforce WCAG AA contrast standards (minimum 4.5:1 for normal text, 3:1 for large text and UI boundaries).

### 3. Responsive & Multi-Directional Layouts
- Design mobile-first or ensure seamless responsiveness across narrow mobile, tablet, and wide desktop screens.
- Avoid clipping, awkward line breaks, or unintended horizontal scrolling.
- For RTL languages (such as Persian and Arabic), ensure proper text alignment, mirrored icons/arrows where appropriate, and correct font rendering.

### 4. Redesigning Existing Interfaces
When asked to redesign or modernize existing work:
- Audit and preserve existing working flows, business logic, valuable brand identity, and accessibility features.
- Address observable friction points (clutter, poor contrast, broken mobile layout) without arbitrarily deleting needed user flows.

---

## Guided Studio Workflow (When Requested)

When guided design is requested by the user, proceed in short, lightweight rounds:

### Step 1: Brief & Direction (Short Round)
- Clarify audience, main task, scope, and visual style preference (e.g., minimalist, modern editorial, dark mode, neo-brutalist, refined corporate).
- If the user has no preference, recommend 2-3 suitable directions and proceed.
- If assets (logo, font, brand palette) exist, incorporate them; otherwise propose a clean, accessible palette and typography system.

### Step 2: Imagery & Media
- Determine media strategy: user-provided assets, SVG/CSS graphics, interactive components/charts, or pure typographic layout.
- Do NOT trigger image generation tools or subagents unless the user specifically asks for generated images.

### Step 3: Reference & Competitor Research (Strictly On-Demand)
- Only conduct web search or competitor analysis if the user explicitly asks for external research (`"تحقیق کن"`, `"رقبا رو بررسی کن"`).
- For standard UI patterns, rely on internal knowledge or installed local tools (such as `ui-ux-pro-max`) rather than slow external browsing.

### Step 4: Preview & Approval (If Requested)
- Deliver an HTML preview or wireframe only when the user explicitly requests a preview before implementation.
- If the user asked for direct implementation, implement directly without imposing an approval roadblock.

### Step 5: Deliverables & Documentation (On-Demand)
- Deliver the working UI code directly to the project files.
- Deliver documentation (`docs/ui-design/` or `project-analysis.md`) **only if requested by the user** or specified in project deliverables.
- Summarize what was created/changed concisely in the user's language with clickable file links.
