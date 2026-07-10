# BrightGrid

**Find the cheapest electricity plan in Victoria, Australia.**

A clean, mobile-friendly web tool that compares electricity plans across all 5 Victorian distribution zones — with full support for solar, battery, and time-of-use tariffs.

## Features

- **Official VDO 2026-27 rates** — ESC-regulated baseline (effective 1 July 2026)
- **500+ VIC postcodes** mapped to distribution zones (AusNet, CitiPower, Jemena, Powercor, United Energy)
- **11 plans per zone** — market offers from major retailers + VDO reference
- **Solar + Battery support** — feed-in credit calculations, export estimates
- **Time-of-Use tariffs** — Peak (4–9pm), Off-peak (9pm–11am), Solar Soak (11am–4pm)
- **Mobile-first design** — responsive, touch-friendly sliders
- **Sunshine yellow theme** — bright, clean, minimal

## How it works

1. **Enter your postcode** — auto-detects your distribution network
2. **Tell us your setup** — solar, battery, daily usage, seasonal grid draw
3. **See results** — plans ranked cheapest to most expensive with annual cost estimates

## Data Sources

- [ESC Victorian Default Offer 2026-27](https://www.esc.vic.gov.au/electricity-and-gas/prices-tariffs-and-benchmarks/victorian-default-offer)
- Market offers based on published retailer rates and VDO discount percentages

## Tech Stack

- Single HTML file (HTML + CSS + vanilla JS)
- No frameworks, no build step, no backend required
- Works offline once loaded

## Live Site

[https://yoghurt16.github.io/BrightGrid](https://yoghurt16.github.io/BrightGrid)

## License

MIT
