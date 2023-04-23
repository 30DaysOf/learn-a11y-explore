# Automatic-a11y

Exploring the tools, resources and process for _automated testing_ of modern web apps and websites, with **accessibility in mind**. Use this section to explore both the opportunities and limitations of current tooling for:
 * local/interactive testing workflows (integrated with development process)
 * automated testing pipelines (built into CI/CD process)

---

## Relevant Resources

This section collects useful resources for self-study along with links to key tools and tutorials for applying them to projects.

> Content

* [Feb 2023](https://opensource.com/article/23/2/automated-accessibility-testing) - "How do I do automated accessibility testing for my website"
* [Oct 2022](https://playwrightsolutions.com/is-it-possible-to-use-playwright-to-do-accessibility-testing/) - "Is it possible to use Playwright to do Accessibility Testing?"
* [Jun 2022](https://www.lambdatest.com/blog/cypress-accessibility-testing/) - "How To Perform Cypress Accessibility Testing"
* [May 2022](https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/) - "A Complete Guide To Accessible Front-End Components (Smashing Mag)"
* [Mar 2022](https://dev.to/steady5063/accessibility-in-javascript-frameworks-part-2-comparing-each-framework-41ch) - "Accessibility in JS Frameworks" (dev.to/Mark Steadman series)
* [Jun 2021](https://frontendmasters.com/courses/accessibility-v2) - "Web Accessibility v2" (Frontend Masters 3h course, Jon K)
* [Aug 2019](https://www.youtube.com/watch?v=IADSsClWVtA) - "Automated & Manual a11y testing with Marcy Sutton" (Cypress)
* [Jun 2019](https://medium.com/@f3igao/how-to-automate-web-accessibility-testing-921512bdd4bf) - "How to automate web accessibility testing" (pa11y)
* [Dec 2017](https://www.24a11y.com/2017/a-developers-guide-to-better-accessibility/) - "Developer's Guide to Better Accessibility" (5 Rules of ARIA)

> Standards & Guides

* [W3C > EARL](https://www.w3.org/TR/EARL10-Schema/) Evaluation and Report Language - vocabulary for test results
* [W3C > JSON-LD](https://www.w3.org/TR/json-ld/) JSON-based serialization format for Linked Data
* [W3C > WCAG > Quick Reference](https://www.w3.org/WAI/WCAG21/quickref/) - How to meet WCAG 
* [WebAIM > WCAG 2 Checklist](https://webaim.org/standards/wcag/checklist#robust) Perceivable, Operable, Understandable, Robust
* [UMich > Accessibility](https://accessibility.umich.edu/guides) - Self-help guides & [strategies](https://accessibility.umich.edu/guides/review-strategies)
* [MDN > Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility) - Mozilla Web Docs on Accessibility, with an [assessment troubleshooting exercise](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Accessibility_troubleshooting)


> Tools

* [axe-core-npm](https://github.com/dequelabs/axe-core-npm) - 7 packages for automated accessibility testing (from `dequelabs`)
* [@axe-core/cli](https://github.com/dequelabs/axe-core-npm/blob/develop/packages/cli/README.md) - commandline interface to axe for quick a11y tests (from `dequelabs`)
* [@axe-core/react](https://github.com/dequelabs/axe-core-npm/blob/develop/packages/react/README.md) - test React applications, see results in DevTools (from `dequelabs`)
* [@axe-core/reporter-earl](https://github.com/dequelabs/axe-core-npm/blob/develop/packages/reporter-earl/README.md) - get  EARL-compliant reports using JSON-LD format
* [@axe-core/playwright](https://github.com/dequelabs/axe-core-npm/blob/develop/packages/playwright/README.md) - chainable axe API for Playwright (from `dequelabs`)
* [cypress-axe](https://github.com/avanslaars/cypress-axe) - community plugin to test accessibility with axe-core in Cypress
* [lighthouse](https://www.npmjs.com/package/lighthouse) - npm package for use with Node CLI
* [playwright](https://www.npmjs.com/package/playwright) - npm package for Playwright Test Runner
* [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) - open-source automated diagnostics with a11y audits
* [Playwright](https://playwright.dev/docs/accessibility-testing) - reliable, e2e, cross-browser, automated accessibility testing
* [Cypress](https://learn.cypress.io/) - reliable, e2e, cross-browser testing (with [real-world examples](https://learn.cypress.io/real-world-examples))
* [Pa11y](https://pa11y.org/) - collection of free, OSS tools for accessibility testing
* [AATT](https://github.com/paypal/AATT) - automated accessibility testing tool from Paypal (axe-core 4.4.2)
* [Lambdatest](https://www.lambdatest.com/blog/curated-tools-for-accessibility-testing-of-websites/) - list of curated tools for a11y testing
* [TPG ARC Toolkit for Page-level Testing](https://www.tpgi.com/arc-platform/arc-toolkit/) - find & fix single-page, on-demand, a11y issues
* [TPG Color Contrast Analyzer (CCA)](https://www.tpgi.com/color-contrast-checker/) - eyedrop tool for contrast check

 ---