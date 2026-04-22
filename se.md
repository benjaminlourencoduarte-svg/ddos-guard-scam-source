## ⚠️ WARNING: Malware Samples

This repository contains **malicious HTML and JavaScript samples** collected for research and educational purposes.  
They are **NOT safe to deploy** on any production website or server.

- The files demonstrate how scam redirectors (Droplora, Camomilegentlenottable, fake Opera pages, etc.) work.
- Opening these files in a browser **will trigger redirects** to scam domains.
- External `<script>` tags may load **live payloads** from attacker infrastructure (e.g., CloudFront, disposable scam domains).
- These samples are provided **only for analysis**. Do not host them publicly or use them outside of a controlled environment.

### Safe Handling Guidelines
- Always open samples in a **sandboxed environment** (e.g., localhost, VM, or isolated lab).
- **Never** upload them to a real web server.
- Keep backups of your clean site files before testing.
- Treat all external script references as **active malware**.

By using this repository, you acknowledge that the files are **malware artifacts** and agree to handle them responsibly.
