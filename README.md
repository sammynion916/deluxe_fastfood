# Restaurant Website (Delux Fastfood)

This repository contains a restaurant website implemented as a static HTML page (with inline CSS/JS) and supporting assets.

## Project Structure

```
luxe Fast food/luxe_fast_food/
├── README.md
├── luxe-fastfood.html            (optional/legacy, if present at root)
├── web/
│   └── luxe-fastfood.html
├── assets/
│   ├── fonts/
│   │   └── Poppins-Regular.ttf
│   ├── images/
│   │   ├── hero1.jpg
│   │   ├── hero2.jpg
│   │   ├── hero3.jpg
│   │   ├── hero4.png
│   │   ├── dish*.png
│   └── └── reviewer*.png
│   
└── (optional Flutter config files, if present)
    ├── pubspec.yaml
    ├── pubspec.lock
    └── analysis_options.yaml
```

## What’s Included (from the HTML page)

- Responsive navbar with mobile menu toggle.
- Hero section slideshow.
- Popular dishes grid.
- Order modal that opens WhatsApp via `wa.me`.
- Smooth scrolling for anchor links.
- Reviews section + footer.

## How to run

### Option A: Serve with a local static server (recommended)
This avoids any relative-path issues with `../assets/...`.

Run from the project root:

```bash
python -m http.server 8000
```

Then open:

- `http://localhost:8000/web/deluxe-fastfood.html`

### Option B: Open directly
- Open `web/deluxe-fastfood.html` in your browser.

(If images don’t load when opened directly, use Option A.)

## Assets

The page references images using relative paths like:
- `../assets/images/...`

So keep `web/` and `assets/` together as shown above.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.
