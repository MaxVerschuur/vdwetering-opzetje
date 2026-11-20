# Van de Wetering — websiteconcept

Independent Dutch design concept for Van de Wetering Tweewielers, Wageningen. Published only in `MaxVerschuur/vdwetering-opzetje`.

## Preview

https://maxverschuur.github.io/vdwetering-opzetje/

Static HTML, CSS and JavaScript; no build required. GitHub Pages should serve `main` from `/ (root)`. No custom domain or CNAME is used. The existing production website and other repositories are outside this project's scope.

For local preview: `python3 -m http.server 8000` from this directory.

## Features

GSAP ScrollTrigger parallax, animated headline, scroll-linked typography and progress, responsive navigation, working category filters, accessible FAQ, reduced-motion support, direct phone/email/directions links. All essential content remains visible if GSAP cannot load.

## Content and assets

Business details, services and opening hours checked against https://vandeweteringfietsen.nl/ on 20 November 2026. No live stock or prices are implied. Bicycle drawings are conceptual SVG illustrations; lifestyle photographs are externally hosted Unsplash images. Fonts load from Google Fonts; GSAP 3.12.5 loads from jsDelivr. External assets need internet access. No analytics, booking backend or contact form is included; booking enquiries use the shop's real telephone/email.
