---
name: ui-studio
license: MIT
description: Guide project-specific UI/UX design, complete-page work, or redesign of existing websites, storefronts, apps, and dashboards. Adapts flexibly to task scope: jumps directly to high-quality implementation for direct requests, or conducts a guided design workflow when requested. Ensures high craft, accessibility, responsiveness, and complete states without unnecessary token bloat or slow multi-step bottlenecks.
---

# UI Studio

UI Studio designs, refines, and builds complete, production-grade, designer-quality user interfaces tailored to each project's purpose and audience. It eliminates generic "AI slop" and delivers modern, visually striking, and tactile designs.

Use the user's language for questions, explanations, and code comments.

---

## Operating Modes (Adaptive Execution)

Always determine the execution mode first to ensure fast, responsive turnaround:

### 1. Direct Implementation Mode (Default for code & UI tasks)
- **When to use:** The user asks to build, modify, restyle, fix, or implement a specific page, screen, component, or layout (e.g., "این صفحه رو طراحی کن", "کامپوننت کارت‌ها رو بازطراحی کن").
- **Behavior:**
  - **Do NOT** conduct a lengthy multi-round interview.
  - **Do NOT** perform automatic web research or competitor scraping.
  - **Do NOT** generate separate documentation files (`project-analysis.md`, `design-spec.md`) unless requested.
  - **Action:** Select an exceptional, modern design aesthetic (Linear dark, Vercel clean, Bento grid, or warm editorial) and immediately implement the code directly in the target files.

### 2. Guided Design Studio Mode (Only when explicitly requested)
- **When to use:** The user explicitly asks for end-to-end design consulting, style discovery, research, or architecture (e.g., "مراحل طراحی رو از صفر با من پیش ببر", "برام استایل‌های مختلف رو پیشنهاد بده").
- **Behavior:** Follow the guided steps below in short, focused rounds (maximum 1-2 questions at a time).

---

## Anti-AI-Slop: Visual Standards & Design Polish

Generic AI templates (flat gray boxes, washed-out purple gradients, centered hero + 3 identical cards) are strictly forbidden. Every interface must feel like it was crafted by a top-tier product designer.

### 1. Banned Cliches & Anti-Patterns
- **NO identical 3-column card rows** with icon-in-circle + title + paragraph.
- **NO washed-out gray backgrounds** (`#f3f4f6`, `#f8fafc`) with flat gray borders.
- **NO generic marketing headlines** without concrete product substance.
- **NO emoji used as UI icons.** Always use clean inline SVG icons (Lucide, Heroicons, Phosphor).
- **NO default system fonts** for Persian (e.g. Tahoma/Arial). Always use modern typography (`Vazirmatn`, `IranSansX`).

### 2. Modern Layout Archetypes
Select an archetype that elevates the specific product:
- **Bento Grid Layout:** Asymmetric cards with varied hierarchy (e.g., 2-column wide featured interactive preview, 1-column stat metric with live indicator, tall feature showcase, micro-widgets).
- **Linear / Raycast Dark Aesthetic:**
  - Deep rich dark background: `#09090b` (zinc-950) or `#0b0f19`, never pure `#000` or washed-out gray.
  - Layered surfaces: `#121215` / `#18181b` with subtle borders (`border-white/10` or `border-zinc-800`).
  - Subtle top/inner glow (`ring-1 ring-white/5` or radial highlight gradient behind key focal points).
  - Pill badges: `px-3 py-1 rounded-full text-xs font-medium bg-white/5 border border-white/10 text-zinc-300`.
- **Stripe / Vercel Clean Light Aesthetic:**
  - Crisp high-contrast white surfaces with razor-sharp borders (`border-zinc-200/80`).
  - Layered elevation with soft diffuse shadows (`shadow-sm hover:shadow-md transition-shadow`).
  - Refined typography with tight tracking on headings (`tracking-tight font-semibold`).
- **Warm Editorial / Modern Luxury:**
  - Warm cream/paper background (`#fcfbf7` or `#faf8f5`) with deep carbon/ink text (`#121212`).
  - Expressive serif or modern geometric grotesk headings, generous whitespace, asymmetric column rhythm.
- **High-Density Dashboard / Pro Tool:**
  - Clean data tables, compact action bars, sticky filters, live status dots (`animate-pulse`), and keyboard-friendly controls.

### 3. Typography & Persian (RTL) Excellence
- **Persian Typography:**
  - Always link and use modern Persian fonts (e.g. `https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800;900&display=swap`).
  - Line-height must be generous for Persian text: `line-height: 1.7` to `1.8` (`leading-relaxed` or `leading-loose`), with body text at minimum `15px` / `16px`.
  - Heading font weight: 700 or 800 for high visual contrast with body copy.
  - Numbers and dates: support Persian numerals (`font-feature-settings: 'ss01'`) where appropriate for localized apps.
- **Hierarchy & Tracking:**
  - Huge scale contrast: Display titles (36px–64px) with tight tracking vs micro-labels (11px–12px uppercase tracking-wider).

### 4. Tactile Micro-Interactions & Depth
- **Hover & Active States:** Every button, card, and interactive row must react to touch/mouse:
  - Cards: `transition-all duration-200 ease-out hover:-translate-y-1 hover:border-zinc-700 hover:shadow-lg`
  - Buttons: Smooth scale on press (`active:scale-[0.98] transition-transform`), high-contrast focus rings (`focus-visible:ring-2 focus-visible:ring-offset-2`).
- **Complete States:** Always design empty states with helpful illustrations/actions, loading skeletons (`animate-pulse`), and contextual inline error messages.
- **Contrast & Accessibility:** Guarantee WCAG AA (minimum 4.5:1 for normal text, 3:1 for large text). Never use low-contrast gray text on gray backgrounds.

---

## Guided Studio Workflow (When Requested)

When guided design is requested by the user, proceed in short, lightweight rounds:

### Step 1: Brief & Direction (Short Round)
- Clarify audience, main task, scope, and visual style preference (e.g., Linear Dark, Clean SaaS, Bento Editorial, Neo-Brutalism).
- If the user has no preference, recommend 2-3 suitable modern directions with clear aesthetic personality.

### Step 2: Imagery & Visual Assets
- Determine media strategy: inline SVG graphics, interactive data visualizations, CSS patterns, or user-provided assets.
- Do NOT trigger AI image generation tools unless explicitly requested.

### Step 3: Reference & Competitor Research (Strictly On-Demand)
- Only conduct web search if the user explicitly asks for external research (`"تحقیق کن"`, `"رقبا رو بررسی کن"`).

### Step 4: Preview & Approval (If Requested)
- Deliver an HTML preview or wireframe only when the user explicitly requests it.
- If direct implementation was asked, apply directly to the codebase.

### Step 5: Deliverables & Summary (On-Demand)
- Deliver the working UI code directly to project files.
- Summarize changes concisely in the user's language with clickable file links.
