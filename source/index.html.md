---
title: Bonsai Documentation


toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:

search: true

layout: home

---

# Bonsai Documentation

Welcome to the sandbox for the future Slate-powered Bonsai documentation site!

<aside class="notice">
This is a temporary landing page.
</aside>

## Draft Sections:

I've set up a draft of the following pages to show off the new format. These are early drafts, and subject to change.

The listed endpoints reflect the site map available at [Coggle](https://coggle.it/diagram/V_RLZO99g4VT4gaT/e87816a3386a4dcf961fcd2df53621233acaf8c1f3c0e2c735189ae0b0d4c90c)

"Everything" pages represent compilations of full sections; I'm gradually going through and correcting name collision. The pages listed below are likely a superset of the pages we would want to link, and we would then use deep-links with anchors to fill out the switchboard.

Page | Status | Style
-------------- | -------------- | --------------
[Getting Started][1] | Second Draft | Modular
[Inkling New][2] | Zeroth Draft | Modular
[Inkling Classic][3] | Second Draft | Modular
Mastermind | Absent | N/A
[References][4] | Second Draft | Modular

# FAQ:

## Where did the **Chapter/Section** numbers go?

These are temporarily removed until the site tree settles down, and will likely be replaced.

## Why are we splitting the [Everything Inkling][3] page?

This body of work includes overlapping sections with similar names, which is confusing to the reader and breaks Slate functionality. In addition, we're conjoining a notional, concept-based approach with a concrete, lexicon-based approach.

That said, the modular nature of this implementation allows us to continue to pursue this approach as long as we address name collision. Further, as they say in my neighborhood, _¿porque no dos?_ Using the modular approach, we can build topical as well as comprehensive Inkling pages out of the same bucket of [includes][6].

## What are Modular pages?

Slate supports the notion of [includes][6], which allow us to put the documentation into a database of sorts and rebuild it from parts. This works by holding the pages in the `includes` folder. A display page is made by adding an `includes` section to the front matter, and then listing the included pages in order.

## What about headers/footers/toc_footers?

These are still being designed. It seems like there's likely to be a full-width header including primary-nav to all sections.

## How do I get back to the beginning?

There's a **Return Home** link in the footer of the table of contents.

[1]: /getting_started.html "Getting Started"
[2]: /inkling_classic.html "Classic Inkling"
[3]: /inkling_everything.html "New Inkling"
[4]: /reference_everything.html "Anaconda CLI instructions"
[5]: /cli_reference.html "CLI Reference"
[6]: https://github.com/lord/slate/wiki/Using-Includes "Using Includes: Slate Documentation"