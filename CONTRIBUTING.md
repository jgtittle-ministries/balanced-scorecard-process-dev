# Contributing to The Balanced Scorecard Process

Thank you for your interest in this book. Readers are welcome to suggest improvements at any level — from typo fixes to substantive content suggestions.

## Three ways to contribute

### 1. Use the "Edit this page" pencil icon (easiest)

On every page of the published site, the top-right of the content area has a small pencil icon. Click it to open the underlying Markdown file on GitHub, where you can:

- Read the raw source
- Edit it directly in the GitHub web UI
- Propose your change as a Pull Request

You'll need a free GitHub account. The PR goes to the author for review.

### 2. File a GitHub Issue

For substantive suggestions, questions, or reports of factual errors, open an Issue at <https://github.com/jgtittle-ministries/balanced-scorecard-process/issues>.

A good Issue includes:
- The page or section you're commenting on (with a link if possible)
- What you observed
- What you'd suggest instead, and why

### 3. Open a Pull Request directly

If you're comfortable with `git` and Markdown, fork the repo, make your edits on a branch, and open a PR. The site is built with Material for MkDocs; the build will run automatically and the PR will show whether your changes pass `mkdocs build --strict`.

## What the author is looking for

Helpful contributions tend to be in one of these categories:

- **Editorial polish.** Typos, grammar, awkward phrasing, clarity improvements.
- **Factual corrections.** Where the prose is wrong about a tool, a research citation, or a published reference.
- **Worked examples.** If you have used a BSCP-style methodology in your own work and have a worked example that would illustrate a chapter's claims more concretely, that's particularly welcome.
- **Cross-references.** Pointers to adjacent literature the author may not have engaged with.

What's harder to incorporate without discussion:

- **Substantive content rewrites** — the book is opinionated and the author's voice is part of its purpose. PRs that change the argument substantively are best filed as Issues first so the direction can be discussed before code.
- **Confidential client material.** This book was developed during the author's consulting career. References to specific clients have been generalized intentionally; please don't add named clients or proprietary detail in contributions.

## Where the live work is

- **Dev (this repo):** changes land here first, get reviewed, and are then mirrored to prod.
- **Prod:** <https://jgtittle-ministries.github.io/balanced-scorecard-process/> — the canonical reading copy.

For most contributors the dev/prod split is invisible — your PR comes in against the dev repo, gets reviewed, and once accepted it appears on prod through the normal mirror workflow.

## Code of conduct

Be kind. The book is a working draft and the author is open to being wrong. Constructive critique is welcome; ad hominem is not.
