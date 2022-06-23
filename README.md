# Harmony Salon and Spa site
This is a demo site for a hair salon, spa, or other beauty business. The site is designed with mobile-first, accessibility, and responsiveness in mind.

**Link to project:** https://harmony-salon.netlify.app

![Site Preview Image](https://github.com/cynthiablack/harmony-salon/blob/main/harmony-salon-site-preview.jpg)

## How It's Made:

**Tech used:** HTML, CSS

Harmony Salon and Spa was built using semantic HTML and responsive CSS. Mobile use was front-of-mind during the design and build phase; accordingly, the site is based on a single-column layout that expands to include more columns and content as the available screen size increases.

## Lessons Learned:

While the site was built from a mobile-first perspective, the primary challenge associated with this project was to complete the site using CSS floats, rather than CSS Flexbox or Grid. This is not optimal design as it requires multiple media queries to ensure usability across screens and potentially impacts accessibility. Semantic HTML was used where possible, but the full-screen columnar layout required multiple non-semantic <div> elements. CSS Flebox, CSS Grid, or even a tool like Bootstrap or Tailwind CSS would allow for a similar layout without compromising accessibility.