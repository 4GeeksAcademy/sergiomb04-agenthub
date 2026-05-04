---
name: AgentHub Intelligence Identity
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#464553'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#777584'
  outline-variant: '#c8c4d5'
  surface-tint: '#544fc0'
  primary: '#1f108e'
  on-primary: '#ffffff'
  primary-container: '#3730a3'
  on-primary-container: '#a9a7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#515f74'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3fc'
  on-secondary-container: '#57657a'
  tertiary: '#242c40'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b4257'
  on-tertiary-container: '#a7afc8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3b35a7'
  secondary-fixed: '#d5e3fc'
  secondary-fixed-dim: '#b9c7df'
  on-secondary-fixed: '#0d1c2e'
  on-secondary-fixed-variant: '#3a485b'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  code-sm:
    fontFamily: monospace
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.6'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  gutter: 24px
  margin: 32px
  max_width: 1440px
---

## Brand & Style

The brand personality of this design system is rooted in **Precision**, **Autonomy**, and **Intelligence**. As an AI Agent SaaS platform, the UI must act as a transparent window into complex automated workflows, projecting a sense of calm control. The target audience consists of enterprise operators and developers who require high-density information without cognitive overload.

The design style is a hybrid of **Minimalism** and **Corporate Modern**. It leverages generous whitespace to separate logical groupings, while maintaining a strict, data-driven structure. The aesthetic prioritizes functional clarity over decorative elements, using subtle tonal shifts and high-quality typography to convey a "high-end" enterprise feel. The emotional response should be one of "effortless power"—the user should feel like they are orchestrating a sophisticated digital workforce through a refined, stable cockpit.

## Colors

The palette is anchored by **Deep Indigo** (Primary) to evoke stability and technological sophistication. **Slate** (Secondary) and **Navy/Slate-900** (Tertiary) are used for structural elements like text and navigation to provide a grounded, professional foundation. 

The background uses a tiered neutral system starting at **Slate-50**, ensuring the interface feels airy and modern. Functional accents are strictly reserved for status-driven data: **Emerald** signifies active agent processes, **Rose** identifies critical failures or errors, and **Amber** warns of latency or configuration issues. This strict color utility ensures that when color appears, it is always meaningful and actionable.

## Typography

This design system utilizes a dual-font strategy to balance character with utility. **Plus Jakarta Sans** is employed for headlines and titles to provide a modern, slightly geometric personality that distinguishes the brand. **Inter** is the workhorse for body copy, data tables, and labels, chosen for its exceptional legibility in high-density environments and systematic weights.

Text hierarchy is enforced through a strict scale. Labels use uppercase styling with increased letter spacing to differentiate metadata from actionable content. Line heights are tuned for readability, with body text utilizing a generous 1.5x ratio to prevent eye fatigue during long monitoring sessions.

## Layout & Spacing

The layout follows a **fluid grid system** built on an 8px rhythmic scale. The primary dashboard uses a 12-column grid with 24px gutters, allowing for flexible card-based arrangements that adapt to various screen sizes.

A consistent 32px outer margin ensures the content never feels cramped against the viewport edges. Spacing between related elements (like an input and its label) is set at 8px, while spacing between distinct sections (like a header and a data table) defaults to 32px. This clear hierarchy of proximity helps users mentally group related AI agent parameters and metrics.

## Elevation & Depth

To maintain a high-end feel, depth is achieved through **Tonal Layers** supplemented by **Ambient Shadows**. Instead of heavy dropshadows, the design system uses subtle shifts in background color to define hierarchy:

1.  **Level 0 (Floor):** Slate-50 (#F8FAFC) - The main application background.
2.  **Level 1 (Card):** White (#FFFFFF) - Used for primary content containers and the navigation sidebar. These feature a 1px border (#E2E8F0) and a very soft, low-opacity shadow (4px blur, 2% opacity).
3.  **Level 2 (Floating):** White (#FFFFFF) - Used for modals and dropdown menus. These feature a more pronounced but still diffused shadow (12px blur, 8% opacity) to indicate they sit high above the base layout.

Interactive elements like buttons use a slight inner shadow when pressed to mimic a physical "click," reinforcing the tactile nature of the tool.

## Shapes

The design system adopts a **Rounded** shape language to soften the industrial nature of data-heavy SaaS. 
- **Standard UI Elements:** Buttons, input fields, and small cards use a 0.5rem (8px) corner radius.
- **Large Containers:** Dashboard cards and modals use 1rem (16px) to create clear visual separation.
- **Badges/Chips:** Status indicators use a full-pill radius to distinguish them from interactive buttons.

This approach creates a modern, accessible silhouette while maintaining enough structural rigidity to appear professional and enterprise-ready.

## Components

### Sidebar Navigation
A minimalist sidebar with a width of 256px. It utilizes a white background with a 1px Slate-200 right border. Icons should be stroke-based (2px weight) using the Slate-600 color, transitioning to Indigo-800 on active states with a subtle 4px vertical pill indicator on the left.

### Metrics Cards
Card containers for high-level data. They feature a Plus Jakarta Sans title (Label-md style), a large "Value" display (Headline-lg), and a "Trend" indicator (Emerald for growth, Rose for decline). The hover state should include a subtle lift effect using a slightly deeper shadow.

### Data Tables
Clean, borderless tables with 16px vertical padding on rows. The header row should have a Slate-50 background. Hover states for rows use a very faint Indigo-50 tint to help users track information across columns. Action buttons within rows remain hidden until the hover state is triggered to reduce visual noise.

### Elegant Modals
Centered overlays with a 40% opacity Slate-900 backdrop blur. The modal header includes a clear title and a simple 'X' close button. Primary actions are always right-aligned in the footer, which is separated by a faint 1px border.

### Buttons & Inputs
Buttons use a solid Indigo background for primary actions and a ghost/border style for secondary. Input fields use a 1px Slate-200 border, which transforms to a 2px Indigo ring on focus, ensuring the active field is never in doubt.