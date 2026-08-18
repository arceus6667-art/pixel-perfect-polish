# Pixel Perfect Polish

TASK: FINAL PIXEL-PERFECT QA AND REFINEMENT

The website has already been implemented.

Do NOT rebuild the project.
Do NOT redesign anything.
Work ONLY on the final QA and refinement stage.

REFERENCES

1. Original Website — SOURCE OF TRUTH

https://www.mhssce.ac.in/IEEE.php

2. Current Output — IMPLEMENTATION REFERENCE

https://github.com/arceus6667-art/pixel-perfect-ieee.git

Use the GitHub repository above as the current implementation/output.

Important: Preserve the existing implementation. Do not restart, restructure, or replace working parts unless required to fix a verified discrepancy.

1. VISUAL QA MODE

Switch from development mode to visual QA mode.

Compare:

REFERENCE vs CURRENT IMPLEMENTATION

Check:

Position

Width / height

Spacing

Typography

Colors

Borders

Images

Alignment

Navigation

Footer

Responsive behavior

Do not accept "approximately similar." Fix visible discrepancies.

2. HEADER QA

Inspect the header carefully.

Verify:

Logo position and size

Header/top-bar height

Navigation height

Menu spacing

Font size/weight/color

Background

Borders

Dropdown arrows

Dropdown positioning

Hover behavior

Fix discrepancies without changing the original design.

3. CONTENT QA

Verify the IEEE page content.

IEEE heading

Check:

Font

Size

Weight

Position

Margin

Body

Check:

Content width

Font

Line height

Paragraph spacing

Color

Alignment

The page must not feel more compressed or more spacious than the reference.

4. COMMITTEE TABLE QA

Compare directly with the reference.

Check:

Table width

Column proportions

Borders

Row height

Header styling

Cell padding

Font size

Alignment

Section spacing

Ensure all 9 committee entries are present.

Do not redesign the table.

5. GALLERY QA

Check:

Image size

Aspect ratio

Position

Spacing

Instruction text

Click behavior

Images must not stretch or distort.

6. FOOTER QA

Compare:

Footer height

Contact layout

Address

Phone

Email

Website

Map

Login links

Copyright

Design attribution

Social/link elements

Vertical spacing

Pay special attention to footer proportions and spacing.

7. RESPONSIVE QA

Test:

Desktop
1920×1080, 1600×900, 1440×900, 1366×768, 1280×800

Tablet
1024×768, 768×1024

Mobile
430×932, 390×844, 375×812, 320×568

At every size verify:

No unwanted horizontal scrolling

Navigation works

Dropdowns work

Text wraps correctly

Images remain proportional

Table remains readable

Footer remains usable

No clipping

No overlap

8. MOBILE NAVIGATION QA

Test:

Open/close navigation

Nested menus

Nested menu closing

Important navigation items

Viewport containment

Content visibility

Preserve the original site's visual character.

9. TYPOGRAPHY QA

Check:

Header

Navigation

Dropdowns

IEEE heading

Body text

Committee heading

Table

Gallery text

Contact details

Login links

Footer

Copyright

Correct only verified differences in:

Font family

Font size

Weight

Line height

Letter spacing

Color

Do not introduce arbitrary fonts.

10. SPACING QA

Inspect:

Header → content

Heading → paragraphs

Paragraph → paragraph

Section spacing

Table spacing

Gallery spacing

Footer spacing

Internal padding

Use consistent spacing based on the reference instead of random margin hacks.

11. COLORS QA

Compare:

Header background

Navigation background

Text

Links

Hover states

Borders

Footer background

Footer text

Do not modernize or replace the reference palette.

12. IMAGE QA

Verify:

Correct asset

Aspect ratio

Dimensions

Cropping

Position

No stretching

No layout shift

If an original asset is unavailable, preserve its intended visual footprint.

13. INTERACTION QA

Verify:

Navigation links

Dropdowns

Mobile menu

Gallery

External links

Email link

Phone link

Login links

Map

No dead buttons or broken interactions.

No console errors.

14. CODE QA

Check for:

Build errors

Console errors

Broken imports

Missing assets

Unnecessary dependencies

Invalid HTML

Incorrect React keys

Accessibility warnings

Duplicated/unnecessary code

Fix technical issues without changing the visual design.

15. THREE REFINEMENT PASSES

Perform all three passes.

PASS 1 — STRUCTURE

Fix:

Layout

Widths/heights

Positioning

Header

Footer

Section order

PASS 2 — VISUAL

Fix:

Typography

Colors

Borders

Spacing

Images

Tables

Alignment

PASS 3 — RESPONSIVE + INTERACTION

Fix:

Mobile navigation

Dropdowns

Responsive table

Images

Footer responsiveness

Links

Hover/focus behavior

16. DO NOT STOP EARLY

Do not stop just because the page renders.

Do not assume structural correctness means visual accuracy.

Continue comparing and refining until the major visible differences are eliminated.

17. FINAL ACCEPTANCE CHECKLIST

Reference inspected

Current GitHub output inspected

Header matches

Logo matches

Navigation matches

Dropdowns match

Mobile navigation works

IEEE heading matches

IEEE content matches

Committee section matches

Committee table matches

Gallery matches

Contact section matches

Map matches

Login section matches

Footer matches

Copyright matches

Typography matches closely

Colors match closely

Spacing matches closely

Images preserve proportions

Desktop tested

Tablet tested

Mobile tested

No unwanted horizontal overflow

No broken links

No console errors

No build errors

All 3 refinement passes completed

FINAL RULE

REFERENCE WEBSITE
↓
VISUAL ANALYSIS
↓
CURRENT IMPLEMENTATION
↓
COMPARISON
↓
CORRECTION
↓
FINAL PIXEL-PERFECT RESULT

Do NOT redesign.
Do NOT modernize.
Do NOT simplify.
Do NOT add unnecessary UI.

Match the reference as closely as technically possible while preserving the existing project.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/fa34d2be-5be4-4f2b-b5f7-0936db66a2bf).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
