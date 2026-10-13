# Lab 03: Web Security in an Event Ticket System

**Author:** Miguel Ángel Coria Vargas  
**Project:** POSESIÓN XXVI  
**Language:** Simple English, written for A2 readers. Technical terms have short explanations.  
**Format:** IEEE conference-style LaTeX using `IEEEtran`. This is a student report, not an IEEE publication.

## Read the report

- [LaTeX source](lab-03-web-security.tex)
- For a PDF: upload the source to Overleaf and use pdfLaTeX. The project needs the standard `IEEEtran` class. Compile twice to resolve references.

## Scope and status

This report describes the system from the author's project summary and gives a security test plan. It is not a completed penetration test or a full security audit.

The four planned tests cover staff access, ticket access, repeated entry, and security logs. **They have not been run for this report.** No new vulnerabilities, screenshots, or test results are claimed.

Active tests need a separate lab with fake users, tickets, and receipts. The live event system is outside the active test scope. A SIEM is a future learning step, not a completed integration.

## Evidence checklist

For each future test, save the goal, lab version, user role, steps, expected result, actual result, and final data state. Mark it as pass, fail, or not enough evidence. Publish only safe evidence with fake data. Hide secrets and full access tokens.

## Earlier labs

- [Lab 01: Red Team and Blue Team](https://github.com/themiguelvargas10/cybersecurity/issues/1)
- [Lab 02: System Hardening](https://github.com/themiguelvargas10/cybersecurity/issues/2)

## Sources

- Author's POSESIÓN XXVI project summary, October 13, 2026.
- [Supabase Auth Audit Logs](https://supabase.com/docs/guides/auth/audit-logs)
- [Cloudflare Workers Logs](https://developers.cloudflare.com/workers/observability/logs/workers-logs/)

