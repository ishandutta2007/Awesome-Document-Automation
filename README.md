# Awesome-Document-Automation

## Top Document Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Template-Driven Generation, Document Assembly & Workflow Automation*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Automation**. These tools generate documents from templates, automate data merging, and streamline the creation of contracts, reports, proposals, and forms at scale.



**Examples** include Templafy, PandaDoc, Conga Documents, Docupilot, Formstack Documents, Windward, HotDocs, Docmosis, Documint, and Plumsail (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom template engines, and transparent document generation — ideal for developers, legal teams, and organizations seeking vendor-independent automation. The open-source ecosystem is anchored by **docxtemplater** (Office document templating), **Docassemble** (guided interviews + assembly), and **AavanamKit** (visual PDF/DOCX design), with strong coverage in Java, Node.js, and Python environments.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Templafy](https://www.templafy.com/)**  

  Enterprise document automation and brand compliance platform that integrates with Microsoft Office, Google Workspace, and Salesforce to ensure on-brand document creation.



- **[PandaDoc](https://www.pandadoc.com/)**  

  Document automation, e-signature, and proposal software with templates, content library, and workflow automation for sales and legal teams.



- **[Conga Documents](https://conga.com/)**  

  Document generation and contract lifecycle management platform for Salesforce, Microsoft, and other CRM/ERP systems.



- **[Docupilot](https://docupilot.app/)**  

  Document automation platform with template-based generation for contracts, invoices, proposals, and reports from various data sources.



- **[Formstack Documents](https://www.formstack.com/products/documents)**  

  Document generation tool (formerly WebMerge) that merges data from forms and apps into templates for PDFs, Word, and PowerPoint.



- **[Windward](https://www.windwardstudios.com/)**  

  Document generation and reporting engine for embedding into enterprise applications, with Java and .NET SDKs.



- **[HotDocs](https://www.hotdocs.com/)**  

  Long-standing document assembly platform for legal, insurance, and financial services with template creation and guided interviews.



- **[Docmosis](https://www.docmosis.com/)**  

  Document generation engine and cloud service with Java and REST APIs for high-volume template-based output.



- **[Documint](https://documint.me/)**  

  Document automation platform for generating PDFs and documents from templates and data.



- **[Plumsail Documents](https://plumsail.com/documents/)**  

  Document generation service for Microsoft Power Automate, SharePoint, and other platforms with template-based processing.



## Open-Source GitHub Projects



- **[Docassemble](https://github.com/jhpyle/docassemble)**  

  Open-source expert system for guided interviews and document assembly, originally built for the legal aid community and now used by courts, government agencies, and businesses worldwide . Authors create branching Q&A interviews in readable YAML with Python logic, which then assemble answers into finished PDF and Word documents from templates . Supports conditional workflows, calculations, and complex document generation without bespoke application code. MIT licensed, with a complete self-contained stack including PostgreSQL, Redis, Celery workers, and document toolchain (pandoc, LibreOffice, TeX Live, tesseract) . Deployable on Ubuntu via cloud marketplace with automated security updates .



- **[docxtemplater](https://github.com/open-xml-templating/docxtemplater)**  

  The most widely adopted open-source library for generating docx, pptx, and xlsx documents from templates, usable in Node.js or the browser . Templates are created in Word, PowerPoint, or Excel by non-programmers — placeholders like `{name}`, loops like `{#users}{name}{/users}`, and conditions are replaced with data . Insert custom XML for formatted text. Extensible via modules including Image, HTML, XLSX, Chart, Slides, Subtemplate, and Table (most modules are paid, with a free open-source core) . MIT licensed core with active maintenance for over 8 years .



- **[AavanamKit](https://github.com/jafranjemal/aavanamkit)**  

  Open-source full-stack ecosystem for designing and generating data-driven PDF and DOCX documents, built on React and Node.js . The **Designer** package provides a WYSIWYG visual canvas with drag-and-drop, resize, rotate, and styling — exported JSON becomes the production template. The **Engine** package is a headless Node.js library that merges templates with live data to produce high-quality native vector PDFs and DOCX files . Features auto-paginating tables, barcode support, conditional rendering, pre-printed stationery alignment, and continuous-roll mode for thermal receipts .



- **[Yumdocs](https://github.com/yumdocs/yumdocs)**  

  Open-source template engine for Word, PowerPoint, and Excel in JavaScript environments . Merges documents with data by executing statements and expressions found in `{{field}}` tags. MIT licensed with zero external dependencies beyond XML parsing (xmldom, jexl, jszip). Simple API: load template, render with data object, save output .



- **[Docx-stamper](https://github.com/thombergs/docx-stamper)**  

  Easy-to-use Java template engine for creating docx documents . 220+ stars on GitHub. Note: limited recent commit activity as of mid-2026 .



- **[Docnamic](https://github.com/mklocke/docnamic)**  

  PHP template engine for OpenDocument (.odt) files based on DOM and ZIP extensions . Templates created with standard WYSIWYG OpenDocument software like LibreOffice. Simple API with `loadTemplate()->setData()->render()`. Nested loops and dynamic images not yet supported. Convert ODT to PDF using unoconv .



- **[Document Templater](https://github.com/m4nd0mb3/document-templater)**  

  Apache-2.0 licensed microservice for template-based document generation built on Node.js, Express.js, and the Carbone library . Supports Word (docx) and PDF template formats with simple API integration. Docker-ready with Swagger documentation endpoint at `/api-docs/`. Designed to fetch data in real time from external APIs .



- **[Aldina](https://github.com/clbrge/aldina)**  

  Open-source engine that turns content and a theme into on-brand, print-grade documents, letters, reports, and decks . Built on ChoirMark, an open document format. Pipeline: ChoirMark → compose (into theme grammar) → gate (admit/reject) → project (PDF). Bounded LLM checkpoints for role inference and repair. Gate admits only pages passing hard checks (fit, contrast, hierarchy). Requires headless Chromium. Dual-licensed AGPL-3.0-or-later with commercial option .



- **[Wraft](https://github.com/wraft/wraft)**  

  Open-source Document Lifecycle Management platform built on open formats (markdown and JSON) for content authoring, collaboration, and distribution . Helps businesses produce structured documents from official letters to contracts. AGPLv3 licensed with self-hosted deployment option .



- **[Quarto](https://github.com/quarto-dev/quarto-cli)**  

  Open-source scientific and technical publishing system built on Pandoc . Combines text, code, visualizations, and advanced layouts in `.qmd` files with executable code blocks. Renders to HTML, PDF, Word, Markdown, EPUB, presentations (Reveal.js), dashboards, and websites. Supports R, Python, Julia, and Observable JavaScript. Ideal for reproducible reports and data-driven documents .



- **[OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)**  

  First Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files . Free, open-source, single binary, no Office installation required. Includes a high-fidelity HTML rendering engine so agents can visually inspect documents rather than guessing from DOM — detecting title overflow, shape overlaps, and layout issues. Rendering is baked into the binary, enabling render→view→fix loops in CI, Docker, or headless servers .



### Additional Strong Open-Source Options



- **LOTemplate** — Document generator for ODT, DOCX, and PDF from template and JSON file. Active development with 23+ stars .

- **Unlawful Assembly** — Client-side web application for legal document assembly with survey designer, DOCX template upload, visual field mapping, and docxtemplater-based generation. TypeScript + Vite stack .

- **OpenDoc Headless** — Agent-driven document production for PDF and editable PowerPoint with browser review loop. `npx @ryanyahya/opendoc-headless init` for workspace setup .

- **MoSage** — Agent-driven document creation for reports and proposals with headless Chromium rendering, auto-pagination, table of contents, and export to PDF/Word/HTML. MIT licensed .

- **python-hwpx** — Pure Python HWPX document parsing, editing, and generation without Hancom Office. Includes MCP server and agent skill for AI workflows .



**Frameworks for building custom document automation**: Combine **docxtemplater** for Office document templating with loops and conditions . Use **Docassemble** for guided interviews and complex document assembly with conditional logic . Deploy **AavanamKit** for visual template design with WYSIWYG canvas and headless rendering . Integrate **Yumdocs** or **Docnamic** for lightweight template merging in JavaScript or PHP environments . For AI-agent-driven workflows, **OfficeCLI** or **MoSage** enable agents to create and refine documents autonomously . Note that true enterprise document automation with content governance, brand compliance, and CRM/ERP integrations remains primarily commercial territory; open-source stacks provide strong template engines, visual designers, and assembly frameworks that require integration for complete automation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Document automation tools handle sensitive business, legal, and personal data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, HIPAA).

- Template quality and data validation are critical. Automated document generation should include review workflows for high-stakes outputs (contracts, legal filings, regulatory submissions).

- The open-source ecosystem provides strong template engines, visual designers, and assembly frameworks, but enterprise content governance, brand compliance, and CRM/ERP integrations remain primarily commercial offerings.



---



**Made for developers, legal technologists, operations teams, and document automation engineers.**  

Let's make document automation more open, transparent, and accessible.
