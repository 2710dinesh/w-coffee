# W Coffee

A React + Vite rebuild of the W Coffee single-page site.

## Start locally

```sh
npm install
npm run dev
```

Vite will print the local preview URL. `npm run build` creates the production site in `dist/`.

## Assets

- The former frame based Pour scene has been replaced with a lightweight SVG tumbler that fills smoothly with scroll. The supplied image frames are retained in `public/images/pour/` but are not loaded by the site.
- `public/images/hero-cafe.png` is an atmospheric generated café illustration/photo, not a verified photograph of the actual Rajajinagar location.

Opening hours are set to 6 AM–midnight in Asia/Kolkata, as confirmed by the user. Google review text is not fabricated; the site links to Google for current reviews.

The menu is presented as a scroll-led book: desktop shows one category on each page of an open spread and the paper leaf rotates around the spine in direct response to scrolling, including reverse scroll; narrow screens show a single page at a time. Category tabs jump to their page, and filters/search remain available above the book.
