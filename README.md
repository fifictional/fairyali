# FairyAli

A curated aesthetic fashion catalog with AliExpress affiliate links.

## Categories

- [Cottagecore](cottagecore.html)
- [Fairycore](fairycore.html)
- [Soft / Sleepy Core](softcore.html)

Each category includes a "no bottoms" variant accessible via the page toggle.

## Project Structure

```
.
├── index.html                    # Landing redirect
├── cottagecore.html              # Cottagecore (full)
├── cottagecore-nobottoms.html    # Cottagecore (tops only)
├── fairycore.html                # Fairycore (full)
├── fairycore-nobottoms.html      # Fairycore (tops only)
├── softcore.html                 # Soft/Sleepy Core (full)
├── softcore-nobottoms.html       # Soft/Sleepy Core (tops only)
├── css/
│   ├── cottagecore.css
│   ├── fairycore.css
│   └── softcore.css
├── img/
│   ├── cottagecore/
│   ├── fairycore/
│   ├── soft-sleepycore/
│   └── shared assets (logos, arrows, headers)
├── js/
│   └── (custom scripts)
└── vendor/
    └── slick/                    # Slick carousel library
```

## Notes

- Built with plain HTML, CSS, and jQuery + Slick carousel.
- Images are organized by aesthetic category.
- Affiliate links direct to AliExpress product pages.
