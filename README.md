# DeckMaster — Card Gaming Hub

A polished, portfolio-ready static website simulating a modern online card gaming interface. Built entirely with **HTML5 and CSS3** — no JavaScript, no frameworks.

## Project Overview

DeckMaster is a responsive multi-page card gaming experience that takes users from a game lobby through deck selection to gameplay strategy. The site features reusable UI components, CSS animations, a consistent design system, and an integrated AI Model Comparison feature (bonus).

**Course:** CSC 4370/6370 — Web Development  
**Track:** D — Card Gaming Hub  
**Extension Pack:** Strategy Table Pack  
**Bonus Feature:** Feature 6 — Model Comparison Cards  
**Team:** Rohan Khandelwal & Mohit Kokane

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Landing page with hero, featured game modes, card preview, and CTA |
| Game Lobby | `lobby.html` | Browse game rooms with status badges, player stats dashboard |
| Deck Table | `deck.html` | CSS Grid gameplay layout with draw pile, play area, discard, and player hand |
| Rules & Strategy | `strategy.html` | Game rules, strategy tips, and AI Model Comparison flip cards (bonus) |

## Features

- **Semantic HTML5** — Proper landmarks, heading hierarchy, ARIA labels
- **CSS Grid + Flexbox** — Complex layouts (game table, card grids, responsive navigation)
- **CSS Variables** — Full design token system for colors, spacing, typography, and shadows
- **6+ Animations** — Card hover lift, card flip (Model Comparison), turn indicator pulse, deal animation, fade-in, float
- **Responsive Design** — Mobile-first with breakpoints at 480px and 768px
- **Accessibility** — Skip links, focus-visible states, reduced-motion media query, screen reader support
- **CSS-Only Mobile Nav** — Hamburger menu using checkbox hack (no JS)
- **Model Comparison Cards** — Flip cards simulating AI strategy comparison (speed, accuracy, risk)

## Technologies

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties, Animations, Transforms, Transitions)
- Google Fonts (Orbitron, Inter)

## Folder Structure

```
Rohan_DeckMaster/
├── index.html              # Home page
├── lobby.html              # Game Lobby
├── deck.html               # Deck Table
├── strategy.html           # Rules & Strategy
├── css/
│   ├── styles.css          # Import hub (loads all partials)
│   ├── base.css            # Design tokens, reset, typography, accessibility, layout utils
│   ├── components.css      # Card, button, badge, playing card, divider
│   ├── navigation.css      # Site header, nav bar, mobile hamburger toggle
│   ├── layout.css          # Hero, page header, game info bar, footer
│   ├── game.css            # Game table, flip cards, lobby rooms, stats, strategy
│   ├── animations.css      # @keyframes + animation utility classes
│   └── responsive.css      # Media queries (tablet, mobile, reduced motion)
├── images/                 # Image assets directory
└── README.md               # This file
```

## How to Run

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Navigate between pages using the top navigation bar

No build tools, servers, or dependencies required.

## Design Decisions

- **Dark theme** with black and gold accents creates a premium gaming atmosphere
- **Orbitron font** for headings reinforces the gaming/tech aesthetic
- **Card-based UI** throughout for visual consistency and component reuse
- **CSS Grid game table** on the Deck Table page simulates real card game layout zones
- **Flip card animation** for Model Comparison leverages `transform-style: preserve-3d` and `backface-visibility`
- **Mobile-first responsive** approach ensures the site works across all device sizes

## Screenshots

*Screenshots to be added after deployment*

## Browser Testing

- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Mobile Safari / Chrome (responsive mode)
