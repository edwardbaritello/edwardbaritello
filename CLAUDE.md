# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is the **GitHub special profile repository** for the user `edwardbaritello`. Because the repository name matches the username, its `README.md` is rendered at the top of the GitHub profile page (https://github.com/edwardbaritello). There is no application code, build system, test suite, or package manifest — the deliverable is the rendered README itself.

The author is a corporate analyst (finance / BI / FP&A) learning to code, "learning in public." The stated intent is that this repo will also accumulate "projects and exercises" over time, so new top-level directories for those projects may appear later.

## Repository contents

- `README.md` — the only meaningful file; content is the GitHub profile card (name, role, badges, intro, current focus, contacts). Written in HTML-in-Markdown (centered `<p align="center">` blocks with Shields.io badges) plus standard Markdown sections.

## Working in this repository

There is nothing to build, lint, or test. The workflow is documentation editing:

- **Preview changes**: render `README.md` as GitHub-flavored Markdown to confirm layout. The centered header and badges rely on raw HTML, which GitHub renders but many local Markdown previewers do not.
- **Validate**: confirm badge image URLs and links (LinkedIn, Shields.io) resolve and that the LinkedIn handle is current.

## Conventions to preserve when editing README.md

- Keep the centered header (`<p align="center">`) using `<b>` for the name and `<sub>` for the role tagline.
- Badges are [Shields.io](https://shields.io) `img.shields.io/badge/...` images; the LinkedIn badge wraps its image in an `<a>` to the profile. Match this style when adding badges.
- Keep prose short and first-person/professional in tone, consistent with a profile card (Intro → Current Focus → What's Here → Contacts).
- The repository has been through many small README iterations (see `git log`); prefer focused, single-purpose commits with clear messages.
