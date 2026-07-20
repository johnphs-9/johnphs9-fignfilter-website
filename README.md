# Fig & Filter

Fig & Filter is a neighbourhood café and roastery built around coffee roasted on site, food made fresh each morning, and a welcoming place to settle in. This website brings that experience online across five thoughtfully designed pages, helping customers explore the menu, arrange catering, meet the founders, and plan their visit.

**Live website:** [johnphs9-fignfilter-website.vercel.app](https://johnphs9-fignfilter-website.vercel.app/)

**GitHub repository:** [johnphs-9/johnphs9-fignfilter-website](https://github.com/johnphs-9/johnphs9-fignfilter-website)

The five-page static website follows the visual direction in `DESIGN.md` and the reference screens in `design/`, while using the supplied copy and photographs from `content/`.

## Technology overview

Fig & Filter is a dependency-free, client-side website built with standard browser technologies. It does not use a framework, package manager, build process, backend, database, or third-party runtime dependency. The finished site is deployed on Vercel, although any conventional static web host can serve the project exactly as it appears in this repository.

| Technology | Use in the project |
|---|---|
| HTML5 | Defines the five documents with semantic landmarks, sections, navigation, lists, images, links, and an opening-hours table. Native accessibility features include heading structure, alt text, skip links, ARIA labels, and current-page states. |
| CSS3 | Provides the shared design system and all presentation through custom properties, responsive media queries, Grid, Flexbox, fluid type and spacing, reduced-motion support, and touch-target sizing. No CSS framework or external font service is used. |
| Vanilla JavaScript | Supplies the mobile navigation toggle using the browser DOM API, `classList`, and `aria-expanded`. There are no libraries, modules, network requests, or application state. |
| JPEG assets | Supplies the eight locally hosted photographs in `images/`. Each image uses a lower-case relative path and manifest-defined alternative text. |
| Markdown | Stores the project documentation, source copy, image manifest, and design specification. Markdown files are authoring references and are not required by the deployed website. |
| Google Stitch | Supported the design and prototyping process, helping establish the visual direction and page-reference screens used to guide implementation. |
| Vercel | Hosts and delivers the production website as a static deployment at the live URL above. |

This architecture keeps deployment simple: the HTML files, `styles.css`, and `images/` directory form the complete runtime application, while Vercel publishes them to the web.

### Home
![Screenshot of Fig & Filter website](assets/scr_main.png)
### Menu
![Screenshot of Fig & Filter menu](assets/scr_menu.png)

## Pages

- `index.html` — home page
- `menu.html` — coffee, kitchen, and bakery menu
- `catering.html` — catering packages and ordering details
- `about.html` — café story, founders, and roasting note
- `visit.html` — address, opening hours, directions, and contact details

All pages share `styles.css`. The only JavaScript is the inline mobile-navigation toggle included on each page.

## Project structure

```text
.
├── index.html
├── menu.html
├── catering.html
├── about.html
├── visit.html
├── styles.css
├── images/             # Deployed copies of the eight supplied photographs
├── content/            # Source copy and original image manifest
├── design/             # Page design references
└── DESIGN.md           # Design system and implementation direction
```

## View locally

The site has no dependencies or build step. Open `index.html` directly in a browser, or serve the folder with any static file server. For example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Implementation requirements

- Plain HTML and CSS, with JavaScript used only for mobile navigation
- Navigation collapses below `768px`
- Layout avoids horizontal scrolling at `375px`
- Body text is at least `16px`
- Links and buttons provide a minimum `44px` touch target
- Each page has one visually primary call to action
- All eight photographs use lower-case local paths and appear only on manifest-approved pages
- Every photograph uses the alt text supplied in `content/images/images.md`
- No externally hosted images
