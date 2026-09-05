# Maths problems

A simple single-page app for practising basic maths in small, manageable steps.

https://russmaxdesign.github.io/maths-problems/

The app currently includes:

- addition tests
- times-table tests up to 12 × 12
- controlled BODMAS tests using brackets, powers, roots, division, multiplication, addition and subtraction

## Why this exists

Maths can become intimidating when several numbers and symbols appear together.

This app is designed to make practice feel simpler by keeping each question focused and predictable.

For BODMAS questions, the app deliberately avoids unnecessarily difficult values. For example:

- division problems resolve to whole numbers
- square roots use perfect squares
- powers stay small
- questions are generated from controlled patterns rather than completely random combinations

The aim is not to make maths harder. It is to help people practise breaking a larger problem into a series of small calculations.

If an answer is incorrect, the app encourages another attempt before revealing the solution. BODMAS questions can also show a worked solution that breaks the problem down step by step.

## How it works

The app is built as a single self-contained HTML file using:

- semantic HTML
- CSS
- vanilla JavaScript

There are no frameworks, libraries, build tools or external dependencies.

JavaScript generates the questions, checks the answers and creates worked BODMAS solutions.

The BODMAS generator uses a set of controlled question patterns so that generated problems stay within a useful learning range instead of producing arbitrary or overly complex maths.

## Accessibility

The interface is intentionally simple and includes:

- programmatically associated form labels
- keyboard-operable controls
- visible focus indicators
- status messages announced using live regions
- feedback that does not rely on colour alone
- straightforward semantic HTML

## Using the app

Open the HTML file in a web browser.

No installation, server or internet connection is required.

The app can also be hosted as a static page, for example using GitHub Pages.
