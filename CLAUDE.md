# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains **Lean365 Solutions**, a comprehensive strategic execution and organizational transformation platform built around the **Flow-State Framework**. The project consists of three main solution areas:

1. **Flow-State Framework** - A 4-stage methodology for transforming strategic intent into organizational instinct
2. **Consulting Services** - Expert guidance, assessments, and consulting resources
3. **Lean365 Platform** - AI-powered technology platform with 5 integrated modules

The repository is structured as a static website with HTML/CSS/JS frontend, comprehensive documentation, and business presentation materials.

## Repository Structure

```
Lean365_Solutions/
├── index.html                          # Main homepage hub for all solutions
├── assets/
│   ├── css/style.css                   # Professional design system with CSS variables
│   ├── js/main.js                      # Interactive functionality (animations, forms)
│   └── images/                         # Lean365 logos, icons, and assets
├── FSF/                                # Flow-State Framework section
│   ├── FSF_Framework.html              # Framework methodology details
│   ├── FSF_Casestudies.html           # Industry success stories
│   ├── FSF Presentation/
│   │   ├── Flow_State_Framework.html   # Interactive slide presentation (7 slides)
│   │   ├── docs/                       # Comprehensive markdown documentation
│   │   │   ├── Flow_State_Framework.md # Core framework whitepaper
│   │   │   ├── Lean365_Overview.md     # Platform overview
│   │   │   └── Lean365_*.md           # Individual module documentation
│   │   └── images/                     # Framework icons and visual assets
│   └── CLAUDE.md                       # FSF-specific guidance (exists)
├── Consulting/
│   ├── resources.html                  # Consulting resources and tools
│   └── Projects/                       # Client project templates and examples
└── Lean365_Platform/
    └── platform.html                   # Platform technology details
```

## Development Commands

This is a **static website project** with no build process:

- **Preview**: Open `index.html` in a web browser
- **Local Development**: Serve from a local web server for best experience
- **No Build Tools**: Direct file editing and browser refresh workflow
- **No Package Manager**: No npm, yarn, or similar dependencies
- **No Testing Framework**: Manual testing in browsers

## Architecture Overview

### Frontend Architecture
- **Static HTML/CSS/JS**: Self-contained files with no external dependencies
- **CSS Variables**: Professional design system in `:root` with brand colors and spacing
- **Vanilla JavaScript**: No frameworks - pure DOM manipulation and event handling
- **Responsive Design**: Mobile-first approach with CSS media queries
- **Component-Based Styling**: Modular CSS classes for consistency

### Content Architecture
- **Hub-and-Spoke Model**: Main index.html serves as central navigation hub
- **Three Solution Areas**: Each with dedicated HTML pages and resources
- **Markdown Documentation**: Comprehensive docs in `/docs` folders for content management
- **Static Assets**: SVG icons, images, and downloadable resources

### Key Technical Features
- **Smooth Scrolling**: Anchor link navigation with offset calculations
- **Intersection Observer**: Fade-in animations on scroll
- **Form Handling**: Client-side validation for consultation forms
- **Mobile Optimization**: Touch-friendly interactions and responsive breakpoints

## Content Standards and Messaging

### Core Framework Concepts
- **Strategy-Execution Gap**: 67% of strategies fail due to execution challenges
- **Flow-State Framework**: 4-stage methodology creating organizational "muscle memory"
- **Competence vs Compliance**: Building capabilities rather than forcing behaviors
- **Daily Practice Engine**: Core mechanism transforming intent into instinct

### Brand Guidelines
- **Primary Color**: `--lean-blue: #2557a7` (Lean365 brand color)
- **Typography**: Segoe UI system font stack for professional appearance
- **Tone**: Professional, consultative, focused on measurable business outcomes
- **Messaging**: Transform strategic intent into organizational instinct

### Key Metrics to Reference
- 77% increase in profitability for enhanced execution capacity
- 3x higher success rate for comprehensive transformation approaches
- 90 days to measurable results across industries
- 40% faster strategic execution, 60% improvement in engagement

## Working with This Repository

### Common Tasks
- **Content Updates**: Edit HTML files directly or update markdown in `/docs` folders
- **Styling Changes**: Modify CSS variables in `style.css` for brand consistency
- **Adding Pages**: Follow existing HTML structure and link from main navigation
- **Asset Management**: Add images/icons to appropriate `/images` folders

### File Editing Guidelines
- **HTML Structure**: Maintain semantic structure with proper heading hierarchy
- **CSS Organization**: Use existing CSS variables and component classes
- **JavaScript**: Keep vanilla JS approach - avoid adding external dependencies
- **Forms**: Follow existing form structure with proper validation

### Presentation Materials
- **Interactive Presentation**: Self-contained HTML file with embedded CSS/JS
- **7-Slide Structure**: Navigation with keyboard shortcuts and fullscreen capability
- **Documentation**: Markdown files provide detailed content for each module

## Important Context

### Business Focus
This is a **legitimate business consulting and technology platform** focused on organizational transformation. All content should maintain professional standards and focus on helping organizations improve strategic execution.

### Existing Documentation
There is already a `FSF/CLAUDE.md` file specifically for the Flow-State Framework section. This root-level CLAUDE.md provides overall repository guidance, while the FSF-specific one covers framework details.

### No Build Pipeline
Unlike typical web projects, this uses a direct edit-and-preview workflow. Changes to HTML/CSS/JS files are immediately visible when refreshing the browser.