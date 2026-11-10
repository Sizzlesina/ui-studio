---
name: ui-studio
license: MIT
description: Guide project-specific UI/UX design, complete-page work, or redesign of existing websites, storefronts, apps, and dashboards. Adapts flexibly to task scope: jumps directly to high-quality implementation for direct requests, or conducts a guided design workflow when requested. Ensures high craft, accessibility, responsiveness, and complete states without unnecessary token bloat or slow multi-step bottlenecks.
---

# UI Studio

UI Studio designs, refines, and builds complete, production-grade, designer-quality user interfaces tailored to each project's purpose and audience. It eliminates generic "AI slop" and delivers rich, comprehensive multi-section experiences for any product domain.

Use the user's language for questions, explanations, and code comments.

---

## Operating Modes (Adaptive Execution)

Always determine the execution mode first to ensure fast, responsive turnaround:

### 1. Direct Implementation Mode (Default for code & UI tasks)
- **When to use:** The user asks to build, modify, restyle, fix, or implement a specific page, screen, component, or layout.
- **Behavior:**
  - **Do NOT** conduct a lengthy multi-round interview.
  - **Do NOT** perform automatic web research or competitor scraping.
  - **Do NOT** generate separate documentation files (`project-analysis.md`, `design-spec.md`) unless requested.
  - **Action:** Select an exceptional, modern design aesthetic, map out the comprehensive domain-specific sections, and immediately implement the code directly in the target files.

### 2. Guided Design Studio Mode (Only when explicitly requested)
- **When to use:** The user explicitly asks for end-to-end design consulting, style discovery, research, or architecture.
- **Behavior:** Follow the guided steps below in short, focused rounds (maximum 1-2 questions at a time).

---

## Comprehensive Page Architecture (The Completeness Engine)

**NEVER summarize any page into 3 lazy sections!** A generic "Hero + 3 Cards + Footer" layout is an immediate failure. Real products across all industries require a full, rich journey (typically **6 to 8 purposeful sections**) to resolve doubts, establish trust, and drive action.

Automatically detect the project domain and implement the corresponding full-depth architecture:

### 1. E-Commerce & Storefronts
1. **Announcement Bar & Smart Header:** Clean high-level nav (3-5 items with `whitespace-nowrap`), live cart badge counter, instant search.
2. **Interactive Split Hero:** Product variants, live stock countdown pill, primary CTA with instant buy.
3. **Interactive Category Rail / Dynamic Filters:** Tabbed switching with instant UI reaction.
4. **Curated Product Bento Grid:** Flagship showcases, micro-specs (e.g. impedance, dimensions), customer star ratings.
5. **Interactive Experience Demo:** Product visualizer, sound demo player, 360 preview, or fitment selector.
6. **Head-to-Head Specification Matrix:** Side-by-side technical comparison table across models.
7. **Bundle & Accessory Builder:** Add-on upsells with instant bundle discount calculator.
8. **Social Proof & UGC Gallery:** Verified customer setups, ratings breakdown, and real feedback.
9. **Interactive FAQ & Trust Footer:** Accordion for warranty/returns, guarantees, and multi-column footer.

### 2. SaaS & B2B Web Applications
1. **Hero with Interactive Product Preview:** Interactive dashboard widget or live demo component.
2. **Social Proof / Customer Logo Wall:** Reputable company badges with subtle monochrome opacity.
3. **3-Step Workflow / How It Works:** Step-by-step visual demonstration of the core user journey.
4. **Deep-Dive Feature Bento Grid:** Asymmetric cards showing live micro-interactions and analytics.
5. **Interactive Integrations Ecosystem:** Searchable or tabbed app integrations (Slack, GitHub, Figma, etc.).
6. **Security, Compliance & Enterprise Trust:** SOC2, GDPR, HIPAA badges, uptime stats, and encryption standards.
7. **Interactive Pricing Calculator / Matrix:** Monthly vs. Annual toggle (with % savings badge).
8. **Customer Case Studies / ROI Metrics:** Hard numbers (+140% conversion, 12ms latency) with testimonial quotes.
9. **Interactive FAQ Accordion & Final CTA Banner.**

### 3. Developer Tools & Infrastructure (APIs, CLIs, Cloud)
1. **Terminal Hero:** Copyable CLI install command (`npm i ...` or `curl ...`) with copy feedback.
2. **Interactive Multi-Language Playground:** Tabbed code snippets (Node.js, Python, Go, Rust, cURL) with syntax styling.
3. **Architecture & Pipeline Diagram:** Visual SVG/CSS dataflow showing input, processing, and output.
4. **Benchmark & Latency Comparison:** Interactive bar chart comparing performance vs. traditional solutions.
5. **Ecosystem & SDKs Grid:** Ready-to-use client libraries with status tags.
6. **Changelog & Release Highlights:** Timeline of recent version upgrades and features.
7. **Documentation Quickstart & Community / GitHub CTA.**

### 4. Dashboards & Internal Analytics Platforms
1. **Metric Overview Bar (KPIs):** Real-time counters, sparkline trends, and status indicators.
2. **Primary Analytics Visualization:** Interactive time-series chart with range selector (24h, 7d, 30d).
3. **Bento Status Cards:** Health checks, memory/CPU usage, error rates, and cache hit ratios.
4. **Responsive High-Density Data Table:** Sticky header, sorting, status badges, and mobile-card transformation.
5. **Recent Activity / Audit Log:** Timeline of recent user actions and system events.
6. **Quick Action Flyout / Modal:** Shortcuts for deployment, user invites, or data export.

### 5. Corporate, Creative Agency & Portfolios
1. **Impact Hero:** Strong thesis statement, custom typography, and dynamic visual anchor.
2. **Selected Case Studies (Bento Showcase):** Large visual cards with measurable client outcomes.
3. **Core Services & Capabilities Matrix:** Detailed service breakdown with deliverables.
4. **Methodology & Execution Process:** 4-phase delivery roadmap (Discover, Design, Build, Scale).
5. **Leadership & Team Spotlight:** Real roles, bios, and social links.
6. **Client Endorsements & Metric Testimonials:** High-trust quotes and verified results.
7. **Interactive Project Inquiry / Budget Scope Form.**

### 6. Healthcare, Clinics & Appointment Booking
1. **Fast Booking Hero Bar:** Select specialist, department, date, and insurance provider.
2. **Services & Medical Specialties Grid:** Clear symptoms/treatment taxonomy.
3. **Doctor & Specialist Directory:** Qualifications, languages, ratings, and next available slot.
4. **Patient Outcomes & Trust Reviews:** Verified patient experiences and recovery statistics.
5. **Facilities & Virtual Clinic Tour:** High-res equipment and hygiene standards showcase.
6. **Insurance Transparency & Cost Guide:** Covered plans, payment installments, and FAQs.
7. **Emergency Contacts & Interactive Location Map.**

### 7. EdTech, Academies & Online Courses
1. **Hero with Live Enrollment Widget:** Syllabus preview, student count, and early-bird discount countdown.
2. **Interactive Curriculum Roadmap:** Expandable module tree with lesson durations and projects.
3. **Instructor Credentials & Industry Background:** Real-world experience and portfolio links.
4. **Interactive Lesson Sample:** Playable audio/video preview snippet.
5. **Student Projects & Graduation Showcase:** Real projects built by alumni with hiring outcomes.
6. **Certification & Accreditation Badges:** Industry-recognized partner certificates.
7. **Tuition Options, Money-Back Guarantee & FAQ.**

---

## 4 Mandatory Pillars of Craft (Strict Quality Standards)

Every interface generated or modified by this skill must strictly follow these 4 non-negotiable pillars:

### Pillar 1: Genuine Font Verification & Typography Excellence
- **Verify Real Font Loading:** Never merely declare a font name in CSS without verifying it loads. Always include explicit `<link rel="preconnect">` and `<link href="...Vazirmatn..." rel="stylesheet">` tags (or local `@font-face` declarations).
- **Enforce Body Font Inheritance:** Set `font-family: 'Vazirmatn', system-ui, sans-serif !important;` on `body` and input/button elements.
- **Persian Text Legibility:**
  - Mandatory line-height: `1.7` to `1.8` (`leading-relaxed` or `leading-loose`).
  - Body text minimum `15px` / `16px`.
  - Contrast weight: 700 to 900 for headings, 400/500 for body.
  - Never allow silent fallback to system Tahoma, Arial, or Times New Roman.

### Pillar 2: Custom-Styled Components (Zero Raw HTML Defaults!)
Every interactive control must look completely bespoke and customized:
- **Custom Select Dropdowns (`<select>`):**
  - Strictly **NO raw native browser select bars**.
  - Must use `appearance-none`, custom SVG chevron arrow, padded background, styled borders (`border-white/10`), and custom dark/light option styles.
- **Custom Radio Buttons & Checkboxes:**
  - Strictly **NO raw native browser radio/checkbox widgets**.
  - Must use custom pill groups, segmented controls, or styled toggle cards with custom SVG checkmarks and smooth active states.
- **Custom Inputs & Sliders:**
  - Styled `<input>` and `<input type="range">` with custom thumb/track, subtle focus rings (`focus:ring-2 focus:ring-amber-500/30`), and no jarring blue outline.
- **Component Arrangement & Rhythm:**
  - Mathematical grid alignment, consistent 16px/24px gutters, no random margins or overlapping elements.

### Pillar 3: Zero UI Slop & Cliché Banning
- **NO identical 3-column card rows** with icon-in-circle + title + paragraph.
- **NO washed-out gray backgrounds** (`#f3f4f6`, `#f8fafc`) with flat gray borders.
- **NO emoji used as UI icons.** Always use clean inline SVG icons (Lucide, Heroicons, Phosphor).
- **NO overloaded navbars or multi-line link wrapping.** Top navbars must contain 3-5 concise, high-level links maximum and MUST always use `whitespace-nowrap` so text never breaks awkwardly into two lines. Keep generous breathing room between logo and nav links.
- **NO placeholder or scaffold copy** ("TODO", "Coming soon", "لورم ایپسوم", fake dead buttons). Every visible button must perform an action or give a feedback toast.

### Pillar 4: Modern Trend Anchors (Current Design Intelligence)
- **Bento Grid Layout:** Asymmetric cards with varied hierarchy (tall metric cards, wide feature previews).
- **Linear / Raycast Dark Aesthetic:** `#09090b` (zinc-950) with layered `#121215` surfaces, `border-white/10`, and subtle radial glows.
- **Stripe / Vercel Clean Light Aesthetic:** Crisp white with razor-sharp borders (`border-zinc-200/80`) and soft diffuse shadows.
- **Tactile Micro-Interactions & Depth:**
  - Cards: `transition-all duration-200 ease-out hover:-translate-y-1 hover:border-zinc-700 hover:shadow-lg`
  - Buttons: Smooth scale on press (`active:scale-[0.98] transition-transform`).
  - Mobile table transformations: Tables gracefully become stacked mobile cards on small screens without horizontal scrolling.
  - Dynamic toasts, filters, and tab state management.
