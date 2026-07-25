# Third-Party Vendor Security Assessment (Demonstration)

A self-contained, single-page demonstration of a **third-party vendor security
assessment** and the **TPRM engineering** behind doing it at scale:

- A **25-question, 5-domain** security questionnaire (governance, access control,
  data protection, incident response, compliance) with a **Yes/Partial/No**
  scoring model, **risk-rating thresholds**, and an interactive **scorecard**.
- A full **assessment report** — strengths, weaknesses/gaps, and a conditional
  **recommendation** with contractual conditions and a review cadence.
- **Automating & scaling TPRM (code)** — a **Python** scoring engine, a **SQL**
  third-party register, **pandas** portfolio analytics, and **PowerShell**
  vendor discovery (third-party OAuth grants via Microsoft Graph).

Methodology aligns with **SIG Lite**, **CSA CAIQ**, and **NIST SP 800-53** TPRM
guidance.

## 🔗 Live demo

**https://smittystuff.github.io/vendor-security-assessment-demo/**

## About

This is an **independent** assessment based solely on publicly available
documentation. It is **not affiliated with or endorsed by Google**; the assessed
vendor is used as an illustrative, real-world example. Verify all findings
against the vendor's current documentation before relying on them.

## Tech

A single `index.html` — no build step, no dependencies. All styling and
interactivity (expandable questionnaire sections, code tabs, scorecard) are
inline vanilla HTML/CSS/JS, so it deploys anywhere static files are served.

## Run locally

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

Part of the portfolio of Steven Smith — Information Security Consultant.
