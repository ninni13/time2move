# time2move

**Take a break. Move your body.**

`time2move` is a lightweight interactive stretching guide designed for people who spend long periods studying, working, or using a computer. Users can select a body area from an interactive front/back body map, follow a short stretch, and use the built-in countdown timer to complete each movement at their own pace.

## Features

- Interactive **Front / Back** body map
- Clickable body-area hotspots with hover labels
- Stretch routines for:
  - Neck
  - Shoulder
  - Wrist
  - Upper Back
  - Lower Back
  - Front Thigh
  - Back Thigh
  - Calf
- 2–3 guided stretches for each body area
- Built-in countdown timer with **Start**, **Pause**, and **Reset**
- **Previous / Next** navigation between stretches
- Timer automatically resets when switching movements
- `Stretch complete!` feedback after each stretch
- `Session complete!` feedback after the final stretch in a routine
- Responsive layout for desktop and mobile
- No database, backend, login, or external API required

## How It Works

1. Choose **Front** or **Back**.
2. Click a highlighted body area.
3. Read the stretch instructions and suggested duration.
4. Press **Start** to begin the countdown.
5. When the timer reaches zero, move to the next stretch manually.
6. Return to the body map at any time to choose another area.

## Design

The interface uses a soft pink and warm neutral color palette with **Cormorant Garamond** typography. The body map is drawn directly in SVG using a simplified mannequin-sketch style, allowing each hotspot to remain interactive without relying on external images.

The desktop layout is designed to fit within a single screen where possible, while smaller screens switch to a stacked responsive layout.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG
- Google Fonts — Cormorant Garamond

The entire application is contained in a single `index.html` file.

## Project Structure

```text
time2move/
├── index.html
└── README.md
```

## Run Locally

No installation is required.

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.

```bash
git clone https://github.com/ninni13/time2move.git
cd time2move
```

Then open `index.html` directly in your browser.

## Interaction Details

- The body map remains visible after a body area is selected.
- The timer stops at `0` and does **not** automatically move to the next stretch.
- Selecting **Previous** or **Next** stops and resets the timer to the new stretch's recommended duration.
- Users can return to the body map without completing the full routine.
- Front and back views expose different body areas where appropriate.

## Development Notes

The interface was refined through multiple iterations, including changes to the body-map style, human proportions, hotspot placement, typography, color palette, responsive layout, and stretch-area coverage.

## License

This project was created as a small interactive web project for learning and demonstration purposes.
