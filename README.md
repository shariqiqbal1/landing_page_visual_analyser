# landing_page_visual_analyser
AI Agent that visually audits landing pages for conversion friction using n8n and Google Gemini 2.5 Vision

# 🛬 AI Landing Page Audit Agent

**An autonomous AI agent that audits "Above the Fold" experiences for higher conversion rates.**

<img width="1005" height="400" alt="landing-page-analyzer" src="https://github.com/user-attachments/assets/b53ee8af-f249-4ff4-a35b-c447ab17993d" />


## 🚀 Overview

The first 5 seconds of a landing page determine whether a user converts or bounces. This n8n workflow acts as an automated **Landing Page Specialist**.

It takes a list of URLs (Squeeze Pages, Click-Through Pages, or Homepages), captures a high-resolution screenshot, and uses **Google Gemini 2.5 Flash** to perform a "Heuristic Analysis." It checks for:
* **Value Proposition:** Is the headline clear and benefit-driven?
* **CTA Prominence:** Is the primary call-to-action visible within the "thumb zone"?
* **Trust Signals:** Are there immediate credibility indicators?

It then autonomously drafts a concise, consultant-style report or cold email highlighting the top friction point.

## ✨ Key Features

* **Visual Intelligence:** Uses Multimodal AI (Gemini Vision) to analyze layout, contrast, and hierarchy—not just code.
* **Speed & Scale:** Optimized with **Gemini 2.5 Flash** for high-volume auditing at low cost.
* **Auto-Reporting:** Syncs findings directly to Google Sheets for easy review.
* **Universal Application:** Works for SaaS, eCommerce, and Lead Gen landing pages.

## 🛠️ Tech Stack

* **Orchestration:** [n8n](https://n8n.io/)
* **Vision Model:** Google Gemini 2.5 Flash
* **Screenshots:** ScreenshotOne (or ScreenshotAPI)
* **Database:** Google Sheets

## ⚙️ How to Use

1.  **Download:** Get the `landing-page-analyzer.json` file from this repository.
2.  **Import:** In n8n, go to "Import from File" and select the JSON.
3.  **Setup Credentials:**
    * **Google Gemini:** Add your API Key.
    * **Screenshot Service:** Add your API key in the HTTP Request node.
    * **Google Sheets:** Connect your Google account.
4.  **Run:** Click "Execute Workflow" to start the audit loop.

## 🤝 Contributing

Built by **[Shariq Iqbal](https://www.linkedin.com/in/shariqi/)**.
Check out my [Full Funnel Auditor](https://github.com/shariqiqbal1/ecommerce-collection-audit-agent) for deep-dive analysis.
