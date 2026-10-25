# AGENTS.md

Instructions for AI coding agents working in this repository.

## What this repo is

The list is `README.md`: dashboard entries grouped by category. This repo holds the list, its license, the check that keeps the README in shape, and the files contributors use. Many entries also get a longer write-up on awesome-dashboards.com. The maintainers write and publish those somewhere else, so there is no site code in this repo and nothing to build for it.

## Non-negotiables

1. Never invent facts. Every claim in an entry (what a product does, whether it is free, what platform it runs on) has to come from something you actually checked, not from memory or a guess.
2. Check every product live before adding or editing its entry. Open the URL and confirm the product exists, works, and matches the description.
3. Follow the entry format and ordering exactly: `- [Name](url) - Description.`, placed in its category in A to Z order, with the sponsor's entry left first and untouched.
4. No counts in headings or intro text. Never write things like "50 dashboards" or put a number in parentheses after a heading. Counts drift as people contribute, so the list never states one.
5. No em dashes or en dashes anywhere in prose you write.
6. Sentence-case headings, everywhere except the `# Awesome Dashboards` title.
7. Disclose affiliation. If an entry is for a product you (or the person you are working for) has a stake in, say so in the pull request description.
8. One entry per pull request. Do not bundle multiple additions, edits or removals into a single PR.
9. Never edit the sponsor's entry or the sponsor block at the top of `README.md`. Those are set by the maintainers only.
10. Open a pull request. Never push directly to the main branch.

## Checking your work

Run `npx awesome-lint` against `README.md` locally if you like. CI runs the same check on every pull request, so it is not required before you open one.

## Recipe for adding an entry

1. Confirm the product is real: open its URL and use it. Confirm it has shipped an update within the last year.
2. Pick the one category it fits best. If it could fit two, pick the more specific one.
3. Write a description: objective, 6 to 16 words, starting with a capital letter and ending with a period, naming what the product does plus what sets it apart. No marketing words, no dashes, no repeating the product's name.
4. Find the entry's alphabetical position within that category (after the sponsor's entry, if that category has one) and insert the new line there.
5. Open a pull request with one entry, and note any affiliation with the product in the PR description.

## Pull request checklist

- [ ] The product is real, live, and was checked directly, not assumed from its marketing site.
- [ ] The product has shipped an update in the last year.
- [ ] Exactly one entry was added, edited or removed.
- [ ] The entry follows the format `- [Name](url) - Description.`.
- [ ] The description is objective, 6 to 16 words, and free of marketing words and dashes.
- [ ] The entry sits in the correct category, in A to Z order.
- [ ] The sponsor's entry and the sponsor block were left untouched.
- [ ] Any affiliation with the product is disclosed in the PR description.
