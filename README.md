# InsightCrunch: Your AI Insight Assistant

[![Demo on Poe](https://img.shields.io/badge/Demo%20on-Poe.com-blue?logo=poe)](https://poe.com/InsightCrunch)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

**InsightCrunch** is an AI-powered insight assistant that transforms raw, qualitative user feedback into structured, prioritized product insights. Designed for product managers, UX researchers, and early-stage teams, InsightCrunch helps you quickly understand what your users are really saying—without wading through pages of unstructured feedback.

Built on Claude-3-Haiku, InsightCrunch distills patterns, highlights urgency, and recommends product actions to keep you grounded in the user voice.

---

## What is InsightCrunch?

InsightCrunch isn’t just a chatbot—it’s your research partner. When you provide qualitative feedback (like app reviews, surveys, or support threads), InsightCrunch returns a detailed, structured report with:

* Core thematic clusters
* Prioritized pain points
* Actionable product recommendations
* Signals & sentiment analysis
* Urgent issues
* Opportunity notes (optional)

This transforms messy feedback into clear direction—helping you build better products, faster.

---

## Features

* Natural language input: Paste in any raw feedback, no pre-formatting needed.
* Research-grade output: Clean, structured insights ready for team discussion.
* Prioritized action items: See what matters most and how to act on it.
* Tone & mood analysis: Understand how users feel—not just what they say.
* Ready for real-world usage: Try it instantly at [poe.com/InsightCrunch](https://poe.com/InsightCrunch).

---

## Table of Contents

* [Usage & Demo](#usage--demo)
* [Input & Output](#input--output)
* [Deployment & Integration](#deployment--integration)
* [Enhancements & Roadmap](#enhancements--roadmap)
* [License](#license)
* [Acknowledgements](#acknowledgements)

---

## Usage & Demo

Try it now on Poe.com:
[Demo Link: poe.com/InsightCrunch](https://poe.com/InsightCrunch)

**Steps to Use:**

1. Open the link and paste in your raw user feedback (multiple comments, reviews, survey answers, etc.).
2. InsightCrunch processes the input and returns a structured, prioritized insight report.
3. Use the output to inform product strategy, roadmap discussions, and design decisions.

---

## Input & Output

### Input

**Type:** Plain text
**Format:** One or more paragraphs of raw, qualitative feedback.

**Example Input:**

```
- "Love the app but it crashes frequently after the latest update."
- "The new dashboard is confusing and hard to navigate."
- "I’d like to see more integrations with other tools."
- "Great customer support, but the app loads slowly sometimes."
```

---

### Output

**Type:** Structured insight report in Markdown format.

**Example Output:**

```
**Thematic Clusters**  
1. Stability & Performance: Users report frequent crashes and slow load times.  
2. Navigation & UX: Confusion around the new dashboard layout.  
3. Feature Gaps: Requests for more integrations with other tools.  

**Prioritized Pain Points**  
- Stability & Performance  
  • Crashes after update (high priority)  
  • Slow load times (medium priority)  

- Navigation & UX  
  • Confusing dashboard layout (high priority)  

- Feature Gaps  
  • Desire for more integrations (medium priority)  

**Suggested Product Actions**  
- Stability & Performance  
  • Investigate crash logs and deploy hotfix for stability.  
  • Optimize load times with caching or code improvements.  

- Navigation & UX  
  • Conduct usability testing on dashboard to refine layout.  

- Feature Gaps  
  • Evaluate most requested integrations and prioritize development.

**Signals & Sentiment**  
- Overall tone: Frustrated but hopeful.  
- Emotions: Frustration over crashes, confusion with UI, appreciation for support.  

**Urgent Issues**  
- Frequent crashes post-update impacting user trust.

**Opportunity Notes**  
- Users value integrations—potential growth opportunity.

```

---

## Deployment & Integration

InsightCrunch is designed to fit into various workflows:

* **API / Automation**: Wrap the prompt logic in an API endpoint to automate insight reports from survey tools, app feedback systems, or CRM logs.
* **Database Integration**: Store insights in knowledge bases or integrate them directly with PM tools like Jira, Notion, or Trello.
* **Team Use**: Perfect for PMs and UX researchers who need quick, actionable feedback synthesis.
* **Custom LLM Models**: While this implementation uses Claude-3-Haiku on Poe, the approach can be adapted to other LLMs or APIs.

---

## Enhancements & Roadmap

**Current Capabilities**

* Clear, structured insight reports
* Actionable product recommendations
* Signals & sentiment summaries
* Urgent issue flagging

**Planned Enhancements**

* Direct API for seamless programmatic usage
* Slack/Discord integration for team collaboration
* Export to CSV/JSON for data tracking
* Sentiment trend tracking across multiple feedback datasets

Have ideas or want to contribute? Open an issue or pull request!

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Acknowledgements

* **LLM Engine**: Powered by Claude-3-Haiku from Anthropic.
* **Poe.com**: Platform hosting InsightCrunch for frictionless testing.
* **User-Centric Insight Best Practices**: Inspired by UX research and product discovery frameworks.

---

## Author & Links

Made by SophiaBhoria7

* GitHub: [SophiaBhoria7](https://github.com/SophiaBhoria7)
* [Demo Link: poe.com/InsightCrunch](https://poe.com/InsightCrunch)

Let’s turn messy feedback into clear product direction!
