# Design System: Xa’an — Mexico Real Estate Search

## 1. Visual Theme & Atmosphere
Xa’an is a **premium, trustworthy, and airy** interface designed to bring order to the scattered Mexico real estate market. The aesthetic philosophy is **"Clinical Luxury"** — combining the precision of a data-driven engine with the warmth of a high-end architectural studio.

*   **Mood:** Serene, confident, and meticulously organized.
*   **Density:** Balanced (5/10) — generous whitespace to allow properties to breathe.
*   **Variance:** Controlled Asymmetry (6/10) — overlapping layers and offset grids to create movement.
*   **Motion:** Fluid & Tactile (7/10) — spring-based animations that respond to scroll and interaction.

## 2. Color Palette & Roles
The palette is centered around **Ink Navy** and **Soft Lavender**, creating a high-contrast yet soothing experience.

- **Pure Canvas** (`#FFFFFF`) — Primary background surface.
- **Lavender Wash** (`#F2E7F6`) — Secondary backgrounds, section highlights, and soft accents.
- **Ink Navy** (`#141821`) — Primary text, buttons, and high-depth containers.
- **Muted Amethyst** (`#756791`) — Secondary text, descriptions, and metadata.
- **Deep Orchid** (`#523575`) — Functional accents, icon backgrounds, and focus states.
- **Vibrant Plum** (`#50267A`) — Primary Call-to-Action (CTA) background.
- **Whisper Border** (`#CCC2ED`) — Structural borders and divider lines.

## 3. Typography Rules
Typography is the core of the brand's authoritative voice.

- **Display & Headlines:** `Inter` (or `Outfit/Geist` for premium refinement) — Extra-tight letter-spacing (`tracking-[-0.075em]`), heavy weights (`font-semibold`), and large scales to command attention.
- **Body:** `Inter` — Relaxed leading (`leading-8`), balanced weight for readability.
- **Metadata/Labels:** `Inter` — Uppercase with wide tracking (`tracking-[0.22em]`) for section headers to provide an editorial feel.
- **Hierarchy Rule:** Use extreme scale differences (e.g., 112px headline vs 14px label) to create "Luxury Tension."

## 4. Component Stylings
*   **Buttons:** Highly tactile. Primary buttons use `Ink Navy` or `Vibrant Plum` with a shadow (`shadow-[#523575]/20`). Secondary buttons use `Whisper Border` or `Lavender Wash`. All buttons have a corner radius of `rounded-2xl` (1rem) or `rounded-full`.
*   **Cards:** "The Floating Tablet" style. Generous corner roundness (`rounded-[30px]`), subtle borders (`border-[#f2e7f6]`), and soft shadows that expand on hover.
*   **Inputs:** Minimalist search bars with glassmorphism backgrounds (`bg-white/70`), backdrop blur (`backdrop-blur-xl`), and integrated icons.
*   **Containers:** Use large corner radii (`rounded-[44px]`) and internal nesting to create a "layered" physical depth.

## 5. Layout Principles
- **Asymmetric Hero:** Utilize overlapping cards and parallax scroll transforms to break the traditional flat layout.
- **Grid Strategy:** Use `max-w-[1400px]` containment with wide gutters (`px-10` or `10vw`) to ensure a spacious feel on large displays.
- **Glassmorphism:** Navigation and overlays must use `backdrop-blur` and semi-transparent backgrounds to maintain context.
- **Mobile-First Collapse:** All multi-column layouts must collapse to a single column below 1024px.

## 6. Motion & Interaction
- **Spring Physics:** Use `stiffness: 110, damping: 22` for a premium, weighty feel.
- **Scroll-Linked Parallax:** Components should subtly rotate (`rotateX`) or scale as they enter the viewport to create depth.
- **Staggered Reveals:** Use cascade delays (`0.08s` increments) when rendering lists or grids to guide the user's eye.
- **Micro-interactions:** Hover states should include subtle Y-axis translations (`y: -8`) and shadow expansion.

## 7. Anti-Patterns (Banned)
- **NO** pure black (`#000000`) — use `Ink Navy` (`#141821`).
- **NO** sharp corners — minimum radius is `0.5rem` unless it's a structural divider.
- **NO** generic AI blue/purple neon glows.
- **NO** overlapping text — ensure clean spatial separation for legibility.
- **NO** "filler" copywriting (e.g., "Unleash your potential"). Be literal and data-focused.
