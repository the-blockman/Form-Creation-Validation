# Form-Creation-Validation

A small repository of examples, utilities and tests for creating accessible, resilient HTML forms and validating their input. Focus is on progressive enhancement: forms work with plain HTML and server validation.

## Contents

- Purpose and goals
- Quick start (plain HTML + JS)

## Goals

- Provide reusable patterns for form markup that is accessible and easy to validate
- Show validation strategies: client-side, server-side, and hybrid
- Provide tests and CI-friendly scripts

## Quick start (static HTML + vanilla JS)

1. Clone the repo:

- git clone <repo-url>

2. Open examples in a browser (no build step required for plain HTML examples):

- open `examples/plain/index.html`

3. Example client-side validation pattern (conceptual):

- mark required inputs with `required` and `aria-describedby`
- validate on submit and on blur
- show a single summary region with errors for screen readers
