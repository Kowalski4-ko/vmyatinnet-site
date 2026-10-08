# Вмятин Нет — client website

Website for a paintless dent repair business in the Krasnodar region.
Designed and built by [KOWALT](https://kowalt.ru) (Veniamin Caryuk).

**Live:** https://вмятиннет.com

## Highlights

- Single-page site, hand-written HTML, CSS and vanilla JavaScript, no framework
- Interactive before/after comparison sliders (pointer events, touch-friendly)
- Scroll reveal animations with `IntersectionObserver`, respecting `prefers-reduced-motion`
- Lazy-loaded images, responsive layout
- Local SEO: Schema.org structured data (JSON-LD), sitemap, Open Graph cover
- Customer reviews from Yandex Maps; click-to-call, MAX, VK, 2GIS and map links
- Cookie consent banner
- Apache `.htaccess` and an nginx config example for deployment

## Run it

Static site, no build step. Open `index.html` or serve the folder:

```bash
npx serve .
```

## Author

Veniamin Caryuk — [Telegram @kowalski4444](https://t.me/kowalski4444) · mcaryuk@gmail.com
