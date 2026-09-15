# Moss & Grain website checks

## Preview status

Prepared as local HTML and CSS source. It has not been published, connected to a service or accepted through a visual browser review.

## Check record

| Check | Status | Evidence and finding |
| --- | --- | --- |
| Visitor understanding | Pass by source inspection | The first screen says “Furniture repair for households,” names the three offered repair areas and uses “See repair options,” which points to `#repair-options`. |
| Content | Pass by source inspection | Fictional status appears before navigation and in the metadata/footer. No testimonial, rating, price, qualification, guarantee, location, contact detail, booking link or result claim appears. |
| Semantic structure | Pass by parser/source inspection | One main landmark, labelled navigation, ordered process, section headings and descriptive anchor text are present. |
| Internal destinations | Pass by automated source check | Every same-page fragment link resolves to an element ID in `index.html`; `styles.css` is present locally. |
| Layout | Unverified visually | Responsive rules stack the hero, headings and process below 760px and remove decorative service marks on narrow screens. Native browser interaction was unavailable, so 375px, 768px and 1440px overflow, clipping and overlap remain to be visually checked. |
| Keyboard | Partly verified by source | All interactive elements are native anchors. A skip link and visible `:focus-visible` style are present. Actual tab order and operation remain unverified without browser interaction. |
| Readability | Partly verified | Body text is 16px with 1.6 line height, headings scale with `clamp()`, and core colour pairs were checked mathematically. Zoom/reflow and rendered line length remain unverified. |
| Behaviour | Pass for source destinations; runtime unverified | Navigation uses local fragments and there is no menu script, form or external destination. Browser console and runtime request inspection were unavailable. |
| Form receipt | Not applicable | The preview contains no form and collects no data. |
| Loading | Pass by source inspection | No JavaScript, images, font downloads or third-party resources. The only stylesheet is local. Rendered layout shift and performance were not measured. |
| Sharing | Partly verified | The title and description accurately label the fictional demonstration. `noindex, nofollow` is set. No canonical URL or share image exists because no production URL or asset was supplied. |

## Contrast evidence

The following contrast ratios are calculated from the declared sRGB values:

- Dark ink `#20251F` on warm paper `#F2EEE4`: **13.47:1**.
- White `#FFFFFF` on moss green `#364F3C`: **8.97:1**.
- Moss green `#364F3C` on warm paper `#F2EEE4`: **7.74:1**.
- Deep timber `#6C402D` on warm paper `#F2EEE4`: **7.52:1**.

These source-value calculations exceed the WCAG 2.x contrast thresholds for normal text. They do not replace rendered inspection of every text treatment.

## Focused refinement

The source review found one content defect: two sentences implied that repair would return furniture to everyday function, although the brief supplied no outcome proof. Those sentences now describe the repair areas and assessment basis without promising a result. The affected content and fragment-link checks passed after the revision. Visual defects cannot be claimed fixed without a supported browser inspection.

## Next verification step

Open `index.html` in a supported native browser, then inspect 375px, 768px and 1440px widths. Check horizontal overflow, clipping, focus visibility, tab order, 200% zoom/reflow, and the browser console. Record only observed results.
