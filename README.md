# ApexType v2026 - free online assessment website 2026

> **ApexType is a browser-based strengths and personality assessment that reveals a visitor's primary archetype and provides a personalized roadmap, with fast delivery through GitHub Pages.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felixdaviscua9280/apextype-core-archetype?style=flat-square)](https://github.com/felixdaviscua9280/apextype-core-archetype)

---

<p align="center">
  <a href="https://felixdaviscua9280.github.io/apextype-core-archetype/">
    <img src="https://img.shields.io/badge/Download-ApexType%20Latest-brightgreen?style=for-the-badge" alt="Download ApexType">
  </a>
</p>

> **[Download ApexType v2026](https://felixdaviscua9280.github.io/apextype-core-archetype/)**

---

[Download Latest Build](https://felixdaviscua9280.github.io/apextype-core-archetype/)

---

## What ApexType Does

ApexType gives users a guided online assessment centered on strengths, personality tendencies, and career direction. Its 50-question experience identifies a core strengths archetype, then connects the result with practical guidance and next steps through a personalized roadmap.

The project runs directly in a web browser and can be published with GitHub Pages, so visitors can access and share it without installing a local application. It also provides a lightweight HTML and JavaScript foundation for site owners who need a structured self-assessment with clear results.

---

## Included Capabilities

- Guided 50-question strengths assessment
- Detection of a user's core strengths archetype
- Personalized roadmap results
- Seven available strengths archetypes
- 21 subtype combinations
- Email submission using a Google Apps Script webhook
- Compatibility with GitHub Pages hosting
- HTML, JavaScript, and Chart.js implementation

---

## Setup

1. Clone the repository or retrieve the project files:
   `git clone https://github.com/felixdaviscua9280/apextype-core-archetype.git
2. Open the `apextype` directory in your editor or hosting environment.
3. Publish the files through GitHub Pages, or open the HTML entry point in a browser to inspect the project locally.

For local testing, open the primary HTML file directly or run a basic static server from the project directory.

---

## Running the Assessment

- Launch the site in a modern browser.
- Answer all 50 assessment questions.
- Examine the generated strengths archetype and roadmap overview.
- When the integration is enabled, submit an email through the Google Apps Script webhook process.
- Apply the results to further career exploration and self-assessment.

To preview the files with a simple local server:

`python3 -m http.server`

Open the local URL printed in your terminal, then navigate to the assessment page.

---

## Project Configuration

The main ApexType settings are defined across the HTML, JavaScript, and related web assets. Integration values, including the connection to Google Sheets, are generally maintained in the front-end source and webhook-related code.

The configuration model includes concepts such as:

```json
{
  "assessmentQuestions": 50,
  "archetypes": 7,
  "subtypeCombinations": 21,
  "emailWebhook": "GOOGLE_APPS_SCRIPT_WEBHOOK_URL",
  "chartLibrary": "Chart.js"
}
```

To modify assessment behavior, inspect the scripts responsible for scoring, result assignment, and the webhook destination.

---

## Requirements and Compatibility

- A current web browser
- Static hosting, including services such as GitHub Pages
- Browser support for HTML and JavaScript
- Chart.js for chart-rendered results
- Optional Google Sheets and Google Apps Script support for collecting emails
- Network connectivity when hosted webhooks or external assets are used

---

## Common Questions

**How can I publish an update?**  
Modify the HTML or JavaScript source, then deploy the updated files to GitHub Pages or another static hosting service.

**Where does the configuration live?**  
Assessment behavior is primarily defined in the front-end source files. Webhook values are maintained within the integration code.

**What should I check if the assessment fails to load?**  
Review the browser developer console, confirm that asset paths resolve correctly, and make sure external scripts and webhook URLs can be reached.

**Is the scoring or archetype system customizable?**  
Yes. The project scripts define the question sequence, scoring behavior, and archetype mapping, allowing each of those areas to be adjusted.

**How is email collection connected?**  
Link the Google Apps Script webhook with your Google Sheets workflow, then confirm that the configured endpoint is correct and accessible.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
