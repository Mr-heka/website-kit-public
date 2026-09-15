---
name: website-kit-public
description: Build or improve a small business website or landing page from the user's business facts and assets, through a checked preview and launch handover. Use for a first website, service page or focused website refresh; not a full application or ecommerce rebuild.
---
# Website Kit

Made by Selr AI. Public guided edition, version 2.

Help me build or improve a website for my business. Use the workflow below in
Claude Code, Codex, or another coding assistant with project-file access. Carry
routine decisions through to a checked preview. This instruction is self-contained:
no private repository, global skill installer, component subscription or paid
service is required. Optional worksheets and a fictional example in the full pack
illustrate the workflow; they are not prerequisites.

## Start in the right place

Read my request and the current project before changing files. Preserve existing
work, instructions, framework, content and working routes. Do not replace a whole
site to improve one page. Work in an isolated copy when changes could overlap.

For a new site, use the project folder I provided. If none exists, explain that a
coding workspace is needed and help me choose an empty folder through the host's
supported interface. Do not write into an unrelated folder or install software
globally. A single-page business site can use ordinary HTML, CSS and minimal
JavaScript. Keep an existing framework; choose extra tooling only for an actual
requirement. A store, membership system or authenticated app needs a separate
scope before implementing payments or personal-data storage.

If this chat cannot edit files or run a preview, produce the business brief, page
outline and clearly labelled source files it can support. State what remains to
be done in a coding workspace. Do not describe a text response as a running site.

## 1. Gather what makes this business different

Use supplied material first. Ask up to three grouped questions initially, only
for missing information that changes the result:

1. **Business and visitor:** what do you sell, to whom, in what area, and what is
   the one action visitors should take? Is this a new site or a specific refresh?
2. **Content and evidence:** existing website, services, approved prices, useful
   differences, common customer questions, and proof you are allowed to show.
3. **Look and assets:** logo, photos, colours, tone, and one or two reference
   websites with a sentence about what you like. References are optional.

If answers are incomplete, record a reasonable design assumption and continue
where possible. Missing business facts remain unknown. Never invent pricing,
customer quotes, qualifications, ratings, client logos, guarantees, availability
or results. Do not manufacture urgency. Clearly identify fictional material in
examples. Ask a focused follow-up if a consequential ambiguity remains; an
initial question limit is not a ban on necessary clarification.

Write WEBSITE-BRIEF.md with: visitor, offer, main action and destination, scope,
verified facts, available proof, assets, assumptions and unresolved launch items.
For an existing page, include what works and the specific problems to fix.

## 2. Shape the content before styling it

Write a concise page outline and draft copy in the brief. Explain the purpose of
each section in one sentence. Use only sections that help the visitor decide:
what is offered, who it is for, how it works, what makes it useful, credible proof,
practical questions and the next step. Do not force every business into pricing
cards, a logo wall, a large FAQ or a sticky sales bar.

The first screen should explain the service, its intended customer and the next
action in plain language. Replace empty claims such as “innovative solutions”
with supplied specifics. Match the CTA to its actual destination: “See services”
for an on-page section, “Email an enquiry” for an email link, or the real booking
action if booking is connected. A button must not promise a workflow it lacks.

When proof is missing, use an honest explanation of the process or relevant work
provided by the user; do not create a fake testimonial. Keep unanswered questions
out of public copy. Show the outline briefly, then continue within the supplied
brief unless the user requested an approval checkpoint or a choice changes scope.

## 3. Choose a coherent visual direction

Follow the business's existing brand. If none is provided, choose one appropriate
direction and explain why it fits the audience. Record the palette, typography,
spacing, content width, image treatment and button style in WEBSITE-BRIEF.md.
Use a small consistent set of CSS variables or the project's existing tokens.

Use references for principles such as hierarchy, density or photography, not to
copy another business's text, code, logo or distinctive artwork. Use owned or
licensed assets; record their source and usage basis. If there are no photos,
build an intentional typography-led layout. Do not fill gaps with broken images
or pretend a stock image depicts the actual business or customer.

Give the main message visual priority. Vary layout only when the content benefits,
keep body text easy to read, and use space to group related information. Avoid
arbitrary gradients, endless identical cards, tiny low-contrast captions and
animations that hide content. Decorative polish cannot repair vague copy.

Before expanding the page, implement the header, first screen and one supporting
section. Inspect that small slice when browser tools are available, then reuse
its established styles. Do not require paid fonts, component generators or an
external design skill to finish this workflow.

## 4. Build a useful preview

Implement semantic HTML, clear headings, labelled controls and real destinations.
Use responsive images with dimensions, and keep the page useful without optional
animation. Respect reduced motion. Navigation and disclosures must work with a
keyboard, with visible focus and controls large enough to operate comfortably.

Design for narrow screens and wider layouts. Let columns stack and text wrap
naturally. Avoid fixed heights
that clip copy, horizontal overflow and sticky elements that obscure controls.
An existing multi-page site keeps its routes and metadata unless the brief changes
them. Avoid duplicate dependencies and unnecessary rebuilds.

Do not make a pretend contact form. If no approved destination exists, use a real
user-supplied contact option, or clearly label the form as an unconnected preview
and list it as a launch blocker. No invented email addresses. Form UI needs labels,
validation, progress, success and recoverable failure states. Success must follow
a confirmed response, not merely a button click. Keep secrets out of client code.
Use server-side validation and appropriate spam controls when connecting a form.
Collect only necessary fields and flag relevant privacy requirements for launch.

Do not enrol contacts, send real messages, purchase services, alter DNS or publish
without authority. Preserve permission already given for a specific action. An
unconnected optional integration should not prevent the rest of the preview.

## 5. Check the result and make one useful refinement

Run the project's existing relevant checks and local preview. With supported
browser tools, inspect 375, 768 and 1440 pixel widths, plus any failing breakpoint.
Record actual checks and findings in WEBSITE-CHECKS.md:

| Check | Evidence to collect |
| --- | --- |
| Visitor understanding | First screen names the offer and visitor; primary CTA describes its real destination |
| Content | No fabricated proof, unresolved public placeholders or contradictory business facts |
| Layout | No horizontal overflow, clipped copy, overlapping controls or distorted images at inspected widths |
| Keyboard | Reach and operate navigation, CTAs and disclosures; focus stays visible and no trap occurs |
| Readability | Check text contrast with a measurement tool; review font size, line length and zoom/reflow |
| Behaviour | Exercise links, menus and validation; inspect console errors, broken requests and missing assets |
| Form receipt | Separate UI validation, authorised test-mode receipt and production receipt; never infer delivery |
| Loading | Inspect image sizes, layout shifts and avoidable blocking resources; measure performance if tools exist |
| Sharing | Accurate title and description; suitable share image if available; canonical URL when known |

Use automated accessibility checks if available, alongside keyboard and visual
inspection. Do not invent scores or claim compliance from a single scan. If a
browser, contrast tool or integration is unavailable, mark those checks unverified
and give the next check to run. A successful build is not visual acceptance.

Compare the rendered page to the stated visual direction. Identify the three most
important concrete defects, or fewer if fewer exist. Fix them, then rerun affected
checks. Do not endlessly restyle or expand the scope. If the design depends on a
missing business choice, present that choice and continue independent checks.

## 6. Hand over clearly; launch only when ready

Deliver the preview or source, WEBSITE-BRIEF.md and WEBSITE-CHECKS.md. Explain how
to open it, where to edit content and which services are connected. Give the user
one practical next step. “Prepared”, “tested locally” and “live” mean different
things; label each accurately.

For an authorised launch, verify the intended account, project and domain before
using the existing deployment route. Review costs and required credentials without
exposing secrets. Resolve public placeholders, broken contact paths and relevant
privacy requirements. Check canonical URL, staging noindex rules and intended
production indexing. Add analytics only when requested or already authorised;
do not silently add advertising pixels.

Preserve a rollback reference. After deployment read back the actual recipient URL,
expected content and assets, and exercise the main action within its authority.
For an authorised form test, use an agreed test destination and verify receipt;
otherwise say delivery remains unverified. Reconcile an uncertain deployment or
submission before retrying it. Hosting, domains and optional services are separate
from this kit; never promise that publishing is free or already complete.

<!-- Provenance marker: sk-13s376t --><!-- Provenance signature: ⁠​‌​‌​​‌‌​‌​​​‌​‌​‌​​‌‌​​​‌​‌​​‌​​​‌‌​​​‌⁠ -->
