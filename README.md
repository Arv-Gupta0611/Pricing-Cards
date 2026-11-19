# Pricing Cards (HTML & CSS)

A responsive three-column pricing card UI built with HTML5 and CSS3 Flexbox, featuring **Basic**, **Standard**, and **Premium** plans with distinct color themes, feature status indicators, and hover animations.

## Features

- **Three Pricing Tiers**:
  - **Basic** (`$2.99 / month`) — Orange accent (`#f97300`)
  - **Standard** (`$5.99 / month`) — Blue accent (`#004f90`)
  - **Premium** (`$9.99 / month`) — Dark gray accent (`#2c2d2e`)
- **Feature Indicators**: Uses green checkmarks (`✔`) for included items and red crosses (`✖`) for excluded items.
- **Equal Default Sizing with Hover Pop-Out**: All three cards start at the same size and smoothly scale up (`transform: scale(1.08)`) with a deeper shadow when hovered.
- **Feature Row Hover Transition**: Individual feature lines (`h4`) subtly shift right (`translateX(4px)`) and darken on hover.
- **Responsive Layout**: Uses Flexbox with `flex-wrap: wrap` so cards adapt across screen sizes.

## Project Structure

```text
.
├── index.html   # Pricing card markup and plan content
├── style.css    # Layout, color themes, and hover/transition styles
└── README.md    # Project documentation