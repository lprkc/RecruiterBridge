# RecruiterBridge

> Paste a job description. Upload resumes. Get real AI feedback for every candidate.

RecruiterBridge is an AI-powered resume screening tool that helps recruiters and hiring managers cut through stacks of resumes by generating personalized, job-specific feedback for each candidate — powered by Claude.

## 📋 Overview

Instead of generic keyword-matching ATS tools, RecruiterBridge analyzes each resume **individually** against your exact job description. Upload up to 10 candidate resumes, paste the JD, and get detailed AI-generated feedback that highlights fit, gaps, and standout qualifications — all in one pass.

## ✨ Features

- **📝 Job Description Analysis** — Paste any JD and have every resume evaluated against its specific requirements.
- **📄 Multi-Format Resume Support** — Accepts PDF, TXT, DOC, and DOCX files (PDF and TXT work best).
- **👥 Batch Screening** — Upload up to 10 resumes at once and get individualized feedback for each.
- **🤖 Personalized AI Feedback** — Each candidate is analyzed independently against your exact JD, not compared to a generic template.
- **🔑 Bring-Your-Own-API-Key** — Uses your personal Anthropic API key, giving you full control over usage and costs.
- **🔒 Privacy-First Design** — Your API key is stored only in your browser's `localStorage` and is never sent anywhere except directly to Anthropic's API.
- **⚡ Simple Workflow** — Three steps: paste JD → upload resumes → generate feedback.

## 🚀 Getting Started

### Prerequisites

- An [Anthropic API key](https://console.anthropic.com) (free to create)
- A modern web browser

<!-- Add any additional prerequisites like Node.js version here -->

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/recruiter-bridge.git

# Navigate to the project directory
cd recruiter-bridge

# Install dependencies
npm install

# Start the application
npm start
```

## 🛠️ Usage

1. **Add your API key** — Paste your Anthropic API key and click "Save Key." It's stored locally in your browser.
2. **Paste the job description** — Drop the full JD into the text field so the AI has full context.
3. **Upload resumes** — Drag and drop (or browse) up to 10 resumes in PDF, TXT, DOC, or DOCX format.
4. **Generate feedback** — Click "Generate personalized feedback" and get per-candidate analysis against the JD.

### Tips

- PDF and TXT files produce the most reliable results.
- For best feedback quality, include the full job description — responsibilities, qualifications, and nice-to-haves.
- Each resume is analyzed independently, so the order of upload doesn't matter.

## 🔒 Privacy & Security

RecruiterBridge is designed to keep your data under your control:

- **Your API key** lives only in your browser's `localStorage` and is sent directly to Anthropic's API — never to any intermediary server.
- **Resume data** is processed through the Anthropic API according to Anthropic's [usage policies](https://www.anthropic.com/legal/usage-policy).
- The application runs client-side, meaning resumes and job descriptions are not stored or transmitted to third-party servers.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue with suggestions and feedback.

## 📝 License

<!-- Add your license information here -->

## ⚠️ Disclaimer

RecruiterBridge is a decision-support tool intended to assist with resume screening. AI-generated feedback should be reviewed by a human recruiter or hiring manager before making hiring decisions. The tool is not a substitute for professional judgment and should not be used as the sole basis for candidate selection. Users are responsible for ensuring their use of the tool complies with applicable employment, privacy, and anti-discrimination laws.
