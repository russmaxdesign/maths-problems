# Maths problems

A single-page app for practising basic maths in small, manageable steps.

https://russmaxdesign.github.io/maths-problems/

The tests build up one step at a time. Each one adds a single new thing to the one before it:

1. **Addition** — two or three whole numbers
2. **Subtraction** — with a second level that crosses below zero
3. **Times tables** — up to 12 × 12
4. **Division** — with a second level giving halves and quarters
5. **Powers** — squares and cubes
6. **Roots** — perfect squares, asked in both directions
7. **Two operations** — no brackets, so the only job is deciding which goes first
8. **BODMAS** — brackets, division, multiplication, addition and subtraction
9. **BODMAS with powers and roots** — Orders added back in
10. **BODMAS below zero** — the same rule, with negative results
11. **BODMAS with halves and quarters** — decimals and negatives at the same time

Every test stays on the page at once, so you can drop back to an earlier one at any point without losing your place.

## Why this exists

Maths can become intimidating when several numbers and symbols appear together.

The app is designed to make practice feel simpler by keeping each question focused and predictable, and by introducing one difficulty at a time rather than all of them at once.

That last point drives the whole structure. A single BODMAS test that mixes brackets, powers, roots, negatives and decimals gives you no way of knowing which skill failed when you get an answer wrong. Splitting them apart means a wrong answer points at something specific.

The values are deliberately kept reasonable:

- divisions either resolve to whole numbers, or are by 2 or 4 only, so a decimal is never worse than .25, .5 or .75
- square roots use perfect squares
- powers stay small
- questions are generated from controlled patterns rather than completely random combinations

The aim is not to make maths harder. It is to help people practise breaking a larger problem into a series of small calculations.

## Reading the notation, not just doing the sums

Two of the tests exist because of a specific and very common misreading.

The **Powers** test mixes questions like `4²` with questions like `4 × 2`, and does not say which one you have been given. Reading the small 2 as something the number is multiplied by is an easy slip, and it can only be practised if both forms turn up unannounced.

The **Roots** test asks the same question in both directions: `√49` and `? × ? = 49`. A root is the question a power answers, and putting the two forms side by side keeps that connection visible.

## Getting an answer wrong

A first wrong answer says so, but does not give the number away. Finding your own slip is a separate skill from doing the arithmetic, and it is the one most likely to be missing. The step most often lost is the easy one straight after the demanding one.

A second attempt reveals the answer and opens the worked solution.

The worked solution breaks the problem into single steps, with the changed number on each line. Where a step crosses below zero it names the size of the gap, and where a division produces a decimal it counts the whole lots and says what the remainder is a fraction of.

The score counts how many you got right first time rather than how many you eventually got right, for the same reason.

## The hint

BODMAS questions have a Hint button. It does not give the answer. It numbers each symbol in the question to show which operation to resolve first, second, third and so on.

Knowing what order to work in and doing the arithmetic correctly are two separate skills, and it is easy to get the right answer using the wrong order without noticing. The hint targets the ordering on its own.

The numbers appear below the symbols rather than inside the question, so the expression itself never changes while you are reading it. Once turned on, the hint stays on for the following questions, because someone who needs it needs it every time.

## How it works

The app is built as a single self-contained HTML file using:

- semantic HTML
- CSS
- vanilla JavaScript

There are no frameworks, libraries, build tools or external dependencies.

JavaScript generates the questions, checks the answers and creates the worked solutions.

Each question pattern declares its own operator order rather than the app parsing the expression afterwards, so the hint numbering and the worked solution cannot drift apart. The displayed expression is assembled from the same list of pieces that carries the ordering, so the question and its hint cannot disagree either.

Every test uses the same behaviour underneath. Which parts are active in a given section is decided by which elements that section actually contains, so a simple addition drill and a full BODMAS drill answer, score and reveal in the same way.

Questions are re-rolled if they repeat one of the last ten asked.

## Accessibility

The interface is intentionally simple and includes:

- programmatically associated form labels
- keyboard-operable controls
- visible focus indicators
- status messages announced using live regions
- feedback that does not rely on colour alone
- straightforward semantic HTML
- a light and a dark colour scheme, both meeting WCAG AA contrast
- hint numbering provided as an ordered list as well as visual badges, with the badges hidden from assistive technology so the question still reads as a plain expression
- space for the hint badges reserved at all times, so revealing a hint does not shift the page
- a numbered contents list linking to each test
- a ± button beside the answer field, because a numeric keypad on iOS has no minus key
- answers accepted in several forms, so `-5`, `(-5)` and a pasted Unicode minus all work

## Using the app

Open the HTML file in a web browser.

No installation, server or internet connection is required.

The app can also be hosted as a static page, for example using GitHub Pages.
