# FUTURE_CS_03 — API Security Risk Analysis Report

**Intern:** Your Name
**Track:** Cyber Security
**Organization:** Future Interns
**Date:** April 2026

---

## Target API
JSONPlaceholder Public Demo API
https://jsonplaceholder.typicode.com

---

## Tools Used
- Postman — API endpoint querying & response inspection
- Browser DevTools — response header analysis
- JSONPlaceholder — safe public demo API target

---

## Assessment Scope
- Read-only GET requests only
- No authentication bypass or destructive testing
- Passive analysis of API responses and headers

---

## Findings Summary

| # | Finding | Risk |
|---|---|---|
| 01 | Unauthenticated Access to User Data | 🔴 High |
| 02 | Excessive Data Exposure | 🔴 High |
| 03 | Missing Rate Limiting | 🟠 Medium |
| 04 | Missing Security Headers on API Responses | 🟡 Low |

---

## Repository Structure
