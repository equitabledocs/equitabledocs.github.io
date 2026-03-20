# EquitableDocs — A Document Equity Initiative

**Accessible documents for every student, in every language, at no cost.**

EquitableDocs is a free document accessibility remediation and Easy Read conversion service for persons with disabilities across the Global South.

We address two distinct but equally critical information barriers identified under UNCRPD Articles 9, 21, and 24:

- **Screen reader accessible formats** — for persons with blindness or low vision who use assistive technologies. We remediate documents to meet WCAG 2.1 AA and PDF/UA standards with proper structural tagging, logical reading order, alternative text, and MathML for mathematical content.

- **Easy Read formats** — for persons with learning disabilities and intellectual disabilities who face barriers when information is presented in complex language or dense layouts. We convert documents into Easy Read versions with clear language, short sentences, meaningful images, and accessible page layouts.

## What This Repository Contains

This repository hosts the public website for EquitableDocs at [equitabledocs.org](https://equitabledocs.org).

The portal application (upload, processing pipeline, admin dashboard) is under active development and will be published in separate repositories:

- `equitabledocs-portal` — Upload and tracking interface for persons with disabilities
- `equitabledocs-pipeline` — Document processing pipeline (OCR, auto-tagging, Easy Read conversion, validation)
- `equitabledocs-admin` — Remediator review dashboard

## The Document Equity Initiative

Document inaccessibility is not a technical inconvenience. For a person who relies on a screen reader, an untagged PDF is a locked door. For a person with a learning disability or intellectual disability, a dense, unformatted document is an equally impassable barrier.

Commercial remediation costs USD 3–4 per page; professional Easy Read conversion costs even more. For persons with disabilities in the Global South, these costs mean inaccessible education, inaccessible public services, and inaccessible civic participation.

The Document Equity initiative exists to close this gap through a combination of enterprise-grade automation, expert human review, Easy Read conversion, and regional language support across 100+ languages.

## Principles

- **"Nothing About Us Without Us"** — Every design decision centres the experience of persons with disabilities
- **Information accessibility is a human right** — Aligned with UNCRPD Articles 9, 21, and 24; India's RPwD Act 2016; and the European Accessibility Act
- **Multiple formats for multiple barriers** — Screen reader accessible PDFs and Easy Read documents are equally essential
- **Automation with human accountability** — AI handles bulk processing; expert remediators ensure quality
- **Free for persons with disabilities. Always.** — EquitableDocs will never charge for remediation or Easy Read conversion

## Technology

The remediation pipeline is built on open-source tools:

- **OCR**: Tesseract 5 + OCRmyPDF (100+ languages), PaddleOCR (complex layouts)
- **Auto-tagging**: PDFix SDK (AI-powered structure detection)
- **Math content**: Mathpix Enterprise (equation recognition, MathML generation)
- **Validation**: veraPDF (PDF/UA compliance checking)
- **Easy Read**: AI-assisted content simplification with expert human review
- **Backend**: Python (FastAPI), PostgreSQL, Redis + Celery
- **Infrastructure**: Docker, hosted on VPS with Cloudflare DNS

## Contributing

We welcome contributions from developers, accessibility specialists, Easy Read authors, Disabled People's Organisations, and disability rights advocates. If you want to help make educational documents and public information accessible for persons with disabilities who need them most, please reach out at deepa@equitabledocs.org or open an issue in this repository.

## Part of The EquitableAccess Suite

EquitableDocs is the flagship platform of The EquitableAccess Suite, which will include:

- **EquitableDocs** — Document accessibility remediation and Easy Read conversion
- **EquitableEvents** — Accessible event management

## License

This website is released under the MIT License. The remediation pipeline repositories will specify their own licences upon release.

---

*Built with the "Nothing About Us Without Us" principle at its foundation.*
