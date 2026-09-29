# Ishtar — AI-powered Web Penetration Testing Framework

**Ishtar** is a modern, GUI-driven web penetration testing framework built with Python and CustomTkinter. It orchestrates security tools into cohesive scanning workflows for automated reconnaissance, vulnerability discovery, and directory brute-forcing.

## Key Features

* **Automated Reconnaissance:** Integrates `subfinder` for subdomain enumeration and `arjun` for hidden parameter discovery.
* **Vulnerability Scanning:** Leverages `nuclei` to execute targeted CVE checks and tech fingerprinting against web targets.
* **Fuzzing & Discovery:** Uses `ffuf` for high-speed directory, endpoint, and file brute-forcing.
* **GUI & Playbook Orchestration:** Offers both semi-autonomous and fully automated scanning workflows managed through an interactive CustomTkinter interface.
* **Markdown Playbook Integration:** Driven by markdown-based playbooks for repeatable security testing methodologies.
* **Actionable Logging & Reporting:** Aggregates multi-tool outputs into structured logs to simplify analysis and reduce false positives.
