# Omar Karani — Portfolio

A responsive personal portfolio for **Omar Karani**, an AI marketing operations specialist, prompt engineer, and strategist based in Nairobi, Kenya.

The site presents Omar's work and point of view through a bold editorial visual system, motion-led transitions, and clear paths to explore his story, experience, impact, testimonials, and contact details.

## Design and experience

- **Editorial art direction:** oversized typography, high-contrast composition, and a portrait-led hero.
- **Purposeful motion:** preloader and reveal transitions, liquid image treatment, and smooth scrolling.
- **Responsive layouts:** CSS breakpoints adapt navigation, spacing, typography, and section layouts for phones, tablets, laptops, and large desktop displays.
- **Touch-friendly navigation:** designed to remain usable on narrow screens as well as pointer-driven desktop devices.
- **Reduced-motion support:** respects the operating system's reduced-motion preference where applicable.
- **Static-site friendly:** the portfolio uses HTML, CSS, and JavaScript without requiring a framework build step.

## Portfolio sections

- **Story** — background, approach, and professional point of view.
- **Experience** — career and selected work context.
- **Impact** — outcomes and areas of expertise.
- **Voices** — testimonials and professional perspectives.
- **Contact** — a direct path to connect.

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser.

No package installation or build command is required for the static version.

## Deployment

This project can be deployed to any static hosting provider, including GitHub Pages or Vercel. For GitHub Pages, open **Settings → Pages**, choose the deployment source, and publish the `main` branch from the repository root.

## Responsive QA

Recommended manual checks before publishing:

| Device class | Suggested viewport | Verify |
| --- | --- | --- |
| Phone | 360 × 800 and 390 × 844 | No horizontal overflow, readable type, accessible navigation, portrait crop, comfortable tap targets |
| Tablet | 768 × 1024 and 1024 × 768 | Section spacing, legible content, and portrait/layout behavior in both orientations |
| Desktop | 1280 × 800 and 1440 × 900 | Overall composition, transitions, typography scale, and footer alignment |

The page includes a viewport meta tag and responsive CSS breakpoints. The checklist is a recommended manual QA pass, not a claim of automated device testing.

## Implementation notes

- Built with HTML, CSS, and JavaScript.
- Google Fonts and any CDN-hosted animation/smooth-scroll libraries require an internet connection.
- Keep contact links and external profile URLs current when updating the portfolio.

## Project goal

A focused professional home for Omar's work across AI, marketing systems, prompt engineering, and strategy — designed to feel intentional across screen sizes and let the work speak clearly.
