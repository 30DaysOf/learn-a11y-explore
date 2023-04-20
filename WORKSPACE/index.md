# Learn A11y | Automate Testing

> **Attribution**: This repo is forked from [jkup/learn-a11y](https://github.com/jkup/learn-a11y) - an open source web app for learning about web accessibility that accompanies _Jon Kuperman's_ [Introduction to Accessibility v2](https://frontendmasters.com/courses/accessibility-v2/introduction/) course on Frontend Masters. It is also meant to stand alone as a workshop for learning web-accessibility with hands-on exercises. 

---

_This page_ documents my learning journey with the resource and my explorations with Playwright in this context.

 * Want to learn about a11y? Fork the [original repo](https://github.com/jkup/learn-a11y) and check out the author's course on [Frontend Masters](https://frontendmasters.com/courses/accessibility-v2)!
 * Want to learn about Playwright usage for a11y? [Star or watch this repo]( https://github.com/30DaysOf/learn-a11y-explore) for my updates and articles.
 * Have feedback (e.g., report bugs, ask questions or request changes)? [Submit an issue](https://github.com/30DaysOf/learn-a11y-explore/issues/new) on this repo.

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

### 2.2 Add WORKSPACE for my updates

Added [a WORKSPACE folder](./index.md) that should be visible at the [/WORKSPACE](https://30daysof.github.io/learn-a11y-explore/WORKSPACE) endpoint on the website. All exploration notes and examples will be created within this folder.

### 2.3 Add sitemap.xml

Sitemaps are typically added to support web crawlers that index sites for search engines. However, they also have value for _automated testing_ as a list of target resources for site that should be prioritized when auditing/testing for performance, SEO, accessibility etc. 

 * Added [WORKSPACE/sitemap.xml](./sitemap.xml) manually following [recommended build practices](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap#text). Using `.xml` (vs `.txt`) format so I can explore [image sitemaps](https://developers.google.com/search/docs/crawling-indexing/sitemaps/image-sitemaps) and extensions later. _This sitemap is not complete, but is functionally correct_.

### 2.4 Add automated-testing

At this point, we have a _deployed website_ on GitHub pages and its _source files_ in GitHub (on the master branch). The course teaches us best practices for _authoring_ accessible websites. In parallel, _automated testing_ can help us detect and report on accessibility issues in our code (in-development) or website (post-deployment) - helping us then apply these learnings in practice.

 * Added [automatica11y/index.md](automatica11y/index.md) subfolder to capture exploration of tools, resources and results, from _automated testing experiments_.

> Setup done! Time to continue with the learn-a11y course!

---

## 3. Learning Notes

> _This section contains my notes from the learn-a11y course_

---

## 4. Testing Notes

> _This section documents notes from my Playwright integration experiments_.

---
