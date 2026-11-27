# Fashionista: E-commerce Store UI

## How to run
Open `index.html` in any browser. Keep `style.css` and the `images/` folder beside it.

use the following link - https://prateeksharmai28.github.io/capstone-ecommerce-website-web-dev-1/

**Theme:** E-commerce Store UI (Web Dev I, Lab Assignment 5, Capstone: Responsive Website Project)
Built with plain HTML5 and CSS3 only (Flexbox and Grid). No JavaScript.

## Sections implemented
- **Header / Nav:** logo, search form, primary internal links, cart, account, login, "Skip to main content" link, CSS-only mobile menu toggle
- **Hero banner:** "Summer Sale is Here!" with a CTA button and a keyframe slide-in animation
- **Flash sale bar:** countdown-style timer
- **Filter sidebar (aside):** category, price and colour checkboxes (visual only)
- **Category cards:** Men, Women, Accessories
- **Product listing:** CSS Grid of six product cards with badges, ratings, prices and Add to cart
- **Product detail:** gallery, colour swatches, size chips, quantity, add-to-cart and wishlist buttons, accordions (`<details>`)
- **Reviews:** three customer testimonials
- **Newsletter:** email form with label and `required`
- **Footer:** link columns, SVG social icons, copyright

## Layout techniques
- Flexbox: header, buttons, card bodies, footer social icons
- CSS Grid: shop layout, product grid, categories, reviews, footer
- CSS variables in `:root` for colours, fonts, spacing
- Relative units (rem, %), `clamp()`, root font size
- Transitions (`all .25s ease`), hover effects, `@keyframes slideIn`
- Respects `prefers-reduced-motion`

## Breakpoints
| Range | Behaviour |
|---|---|
| >= 1400px | Wider container, taller hero |
| <= 1023px | Narrower sidebar, 2-column footer |
| <= 768px | Header items stack, hamburger menu, all grids single column |
| <= 480px | Smaller hero text, stacked subscribe form, 1-column footer |

## Images
All images in `images/` are original SVG illustrations (small file size, sharp at any size) with meaningful `alt` text.
