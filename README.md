# Tooltip UI Component

This repository holds my fully responsive, pure CSS solution to the [Tooltip UI Component](https://roadmap.sh/projects/tooltip-ui) challenge on roadmap.sh.

## Project Details
The target objective of this build is to formulate a refined web navigation layout containing structural **HTML5 and CSS tooltips** triggered securely without depending on scripts or third-party interaction nodes.

## Features & Requirements Met
- **No JavaScript Trigger Engine:** Relies exclusively on CSS styling combined with standard structural hover selectors (`.nav-item:hover .tooltip-box`).
- **Dynamic Micro-Animation Variant Suite:** Custom-engineered four distinctive aesthetic interpolation states leveraging variable transform frames:
  - **Home Link:** Standard alpha opacity linear fade.
  - **Projects Link:** Smooth transitional vertical slide-up tracking.
  - **Blog Link:** High-impact exponential expansion scale curve (`cubic-bezier` pop).
  - **Contact Link:** Downward vertical sliding ease profile.
- **Dynamic Dark Adaptation Profiles:** Monitors theme conditions using global color variable matrices aligned with user preference systems (`prefers-color-scheme`).
- **Fluid Positioning Infrastructure:** Centered perfectly using layout transforms (`translateX(-50%)`) to protect tooltip tracking across arbitrary link string boundaries.

## Setup & Preview
To preview this project locally:
- Clone this repository to your local machine.
- Open index.html directly inside any modern web browser.