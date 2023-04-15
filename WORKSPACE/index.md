# Learn A11y | Automate Testing

> **Attribution**: This repo is forked from [jkup/learn-a11y](https://github.com/jkup/learn-a11y) - an open source web app for learning about web accessibility that accompanies _Jon Kuperman's_ [Introduction to Accessibility v2](https://frontendmasters.com/courses/accessibility-v2/introduction/) course on Frontend Masters. It is also meant to stand alone as a workshop for learning web-accessibility with hands-on exercises. 

---

_This page_ documents my learning journey using that resource, with an extension focused on _exploring_ ideas to apply learnings to my projects using automated testing with Playwright.

If you want to learn about accessibility, I encourage you to visit and fork the [original repo](https://github.com/jkup/learn-a11y) instead.

If you want to explore automated testing ideas alongside me, [star or watch this repo]( https://github.com/30DaysOf/learn-a11y-explore) for updates, and [use issues](https://github.com/30DaysOf/learn-a11y-explore/issues/new) to send me feedback (e.g., report bugs, ask questions or request changes).

---

## 1. Purpose

I have 2 goals with this project:
 * `Learn web accessibility` - from standards and common issues to best practices for developing modern apps.
 * `Build a testing harness with Playwright` that captures core tests in a reusable specification and workflow that I can apply to various projects, to detect and report a11y issues in dev preview or deployed websites.

----

## 2. Changes

This section will document any changes I make in my fork, to the original codebase.

### 2.1 Deploy to GitHub Pages

The original repo built and deployed the project to Netlify. I am instead deploying my fork to the _GitHub Pages_ endpoint on this repo. Changes made:

- [X] - Updated repo [Settings > Pages](https://github.com/30DaysOf/learn-a11y-explore/settings/pages) to deploy from `Branch > master > /(root)`. Saved changes.
- [X] - Validated [Actions were activated](https://github.com/30DaysOf/learn-a11y-explore/actions) to deploy project to GitHub Pages.
- [X] - Validated that [GitHub Pages Site](https://30daysof.github.io/learn-a11y-explore/) was live and deployed correctly.

### 2.2 Add EXPLORE.md for notes

Added [an WORKSPACE folder](./index.md) (containing this file with notes) to capture exploratory ideas. This should be visible at the [/WORKSPACE](https://30daysof.github.io/learn-a11y-explore/WORKSPACE) endpoint on the website.

### 2.3 Add sitemap.xml

Sitemaps are typically added to support web crawlers that index sites for search engines. However, they also have value for _automated testing_ as a list of target resources for site that should be prioritized when auditing/testing for performance, SEO, accessibility etc. 

Adding an [EXPLORE/sitemap.xml](./sitemap.xml) file that follows the [recommended build practices](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap#text) and will come in handy later when exploring Playwright tests. I'm electing to use `.xml` rather than simple `.txt` format since we also want the ability to support [image sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/image-sitemaps) and other sitemap extensions. _This sitemap is not complete, but is functionally correct_.

### 2.4 Add automated-testing

At this point, we have a _deployed website_ on GitHub pages and its _source files_ in GitHub (on the master branch). The course teaches us best practices for _authoring_ accessible websites. In parallel, _automated testing_ can help us detect and report on accessibility issues in our code (in-development) or website (post-deployment) - helping us then apply these learnings in practice.

Adding the [automatica11y/index.md](automatica11y/index.md) subfolder to capture exploration of tools, resources and results, from _automated testing experiments_.

---

## 3. Learning Notes

This section will document my notes and insights from walking through the learn-a11y exercises. 
Primary goal is to document best practices and ideas for how I can apply these to my real-world projects..

---

## 4. Testing Notes

This section will document my notes and insights from adding Playwright and automating tests to detect and report a11y issues in a way that aligns with the learnings above. 
Primary goal is to create a _reusable test specification_ I can then customize for various real-world projects, to detect a11y issues.

---
