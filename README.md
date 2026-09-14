# Magnexis Quantum

![Magnexis logo](assets/magnexis-logo.png)

[![Site](https://img.shields.io/badge/site-GitHub%20Pages-222?logo=githubpages&logoColor=white)](https://theworker02.github.io/magnexis-quantum/)
[![Access requests](https://img.shields.io/badge/access-GitHub%20Issues-155EEF?logo=github)](https://github.com/theworker02/magnexis-quantum/issues/new/choose)
[![Information site](https://img.shields.io/badge/type-static%20information%20site-0E1C35)](https://github.com/theworker02/magnexis-quantum)
[![Program](https://img.shields.io/badge/program-independent%20engineering%20research-5B6B85)](https://github.com/theworker02/magnexis-quantum)

Magnexis Quantum is an independent engineering research program exploring carefully scoped quantum-computing systems, supporting infrastructure, and the evidence needed to develop them responsibly.

This repository is the public information site for the program. It is designed for GitHub Pages and contains no private engineering plans, controlled drawings, manufacturing files, account system, document-delivery backend, credentials, or access-controlled material.

## Request manufacturer material access

Use a **GitHub Issue** to request consideration for access to private partner material. Issues are the preferred route because they are tracked, reviewed sooner, and receive more focused consideration. GitHub Discussions are available for general questions or an initial conversation.

A strong request explains:

- Your organization or professional role.
- Relevant manufacturing, fabrication, laboratory, supplier, installation, engineering-review, or validation capability.
- The intended evaluation or partnership scope.
- Why the requested material would support that scope.

Do not include confidential information, credentials, export-controlled material, or personal-identification data in a public Issue or Discussion.

## Partnership boundary

Private material may be considered for suitable manufacturers, fabrication facilities, laboratories, suppliers, installers, reviewers, and engineering organizations. An invitation is an opportunity to assess a possible collaboration; it is not production authorization.

The responsible manufacturer, laboratory, supplier, installer, or engineering organization must complete and own the detailed design, process definition, material selection, inspection, safety, compliance, commissioning, validation, and qualification work for its scope. Conceptual, calculated, simulated, measured, and accepted material have different meanings. No proposal or simulation alone authorizes manufacture, cryogenic operation, pressure work, lifting, electrical work, site installation, or a qualified quantum computer.

## Program focus

Magnexis Quantum organizes inquiry around:

1. System foundations: requirements, architecture, materials, physical qubits, and interfaces.
2. Operation and control: cryogenics, readout, electronics, error correction, and software.
3. Integration and evidence: facilities, assembly, procurement, validation, and maintenance planning.

The program is independent. It does not represent a university, grant qualifications, or claim institutional affiliation.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Enable **Issues** and **Discussions** in repository settings.
3. In **Settings → Pages**, select **Deploy from a branch**, choose `main`, then choose `/(root)`.
4. Wait for GitHub Pages to publish the site.
5. If a custom domain is used, set `githubRepository` in `assets/site.js` to `owner/repository`. Standard `owner.github.io/repository` URLs are detected automatically.

The structured access-request form is stored at `.github/ISSUE_TEMPLATE/manufacturer-access.yml`.

## Repository contents

- `index.html` — public program and access-request page.
- `assets/site.css` — responsive local stylesheet.
- `assets/site.js` — GitHub Issue/Discussion link resolution and custom-domain setting.
- `.github/ISSUE_TEMPLATE/` — preferred manufacturer-material access request form.
- `.nojekyll` — serves the static site without Jekyll processing.

## Local preview

Open `index.html` directly in a browser, or run a simple local static server:

```sh
python -m http.server 8000
```

Then open `http://127.0.0.1:8000`.

## Security and confidentiality

This site is intentionally public-facing and informational. Do not add private plans, supplier quotations, security-sensitive facility data, credentials, personal data, or access-controlled documents to this repository. Keep private engineering materials in the separate invitation-only repository and grant access only after an appropriate review.

## Release status

`v1.0.0` is the initial GitHub Pages information-site release. It provides a lightweight public program overview and a clear, tracked route for prospective manufacturing partners to request access.


