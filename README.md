# Hashnode articles backup

A mirror of the articles published on [my Hashnode blog](https://hashnode.com/@fbuireu), one markdown file per
article, written here by Hashnode's own GitHub backup integration.

## What is in here

Each file is a whole article: YAML front matter with the title, the publication date, the `cuid`, the `slug`,
the cover image and the tags, then the body in markdown. The SEO fields and `ogImage` appear only where the
article on Hashnode sets them, so a missing `seoTitle` is not a broken backup.

**The filename is the article's `cuid`**, Hashnode's internal identifier, not its slug, so the tree reads as a
row of meaningless names and the front matter is the only place the title appears. Leave the names alone: the
integration writes each article to its `<cuid>.md`, so a renamed file is no longer the one it updates, and the
next sync of that article would most likely write a fresh `<cuid>.md` beside the renamed copy.

| File | Article |
| --- | --- |
| [`cktpx20qe0anwpvs1c03t357u.md`](./cktpx20qe0anwpvs1c03t357u.md) | What is Redux? Do I need to use it? |
| [`clw9npns5000109lffhwtf9jt.md`](./clw9npns5000109lffhwtf9jt.md) | Crafting a custom Breadcrumb component in Astro: Step-by-Step Guide |
| [`clztmm1of000z09l36fhv6ml1.md`](./clztmm1of000z09l36fhv6ml1.md) | Floating Math Point: The Phantom Menace of Precision |

## How it is updated

Hashnode pushes here when an article is published or edited. **Nothing in this repository is edited by hand:**
a change made here does not travel back to Hashnode, and the next sync overwrites it. Fix the article on
Hashnode and let the backup follow.

## Licence

The code samples are covered by [`LICENSE`](./LICENSE), the GNU General Public License v3.0 (GPL-3.0). The
prose is mine, and the cover images are hosted by Hashnode under whatever terms their sources carry.
