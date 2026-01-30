# trizel-site

## Repository Role: Presentation Shell (Layer-2)

This repository serves exclusively as a **presentation-only repository**. It is the static deployment source for the trizel-ai.com website and contains only HTML/CSS/JavaScript for rendering pre-approved content.

### What This Repository Is NOT

- **NOT a scientific content repository**: This repository contains NO scientific content, NO governance rules, and NO authoritative references.
- **NOT a data processor**: It does NOT generate, interpret, or analyze data.
- **NOT citable**: It MUST NOT be cited as a scientific or institutional source.
- **NOT authoritative**: It carries zero epistemic authority.

### Contrast with trizel-site-artifacts

This repository is fundamentally different from `trizel-site-artifacts`:

- **trizel-site-artifacts** is the authoritative institutional content ledger that contains all canonical scientific content, governance rules, and institutional references.
- **trizel-site** (this repository) only renders already-approved, frozen Layer-2 content for web presentation.
- **trizel-site-artifacts** has epistemic authority; **trizel-site** has zero epistemic authority.

This repository simply provides a visual interface for content that has been validated, versioned, and frozen elsewhere.

### Non-Authority Declaration

**This repository serves exclusively as a static presentation shell. It carries no epistemic, scientific, or governance authority. All authoritative content is defined and versioned elsewhere.**

The purpose of this repository is limited to:
- Hosting static HTML/CSS/JavaScript for web presentation
- Serving as the deployment source for trizel-ai.com
- Rendering already-approved institutional content

### Rationale for Separation

This strict separation between presentation (trizel-site) and content (trizel-site-artifacts) exists for critical institutional reasons:

1. **Auditability**: Separating presentation from content ensures that changes to the user interface cannot be confused with changes to scientific or institutional content.
2. **Scientific Integrity**: By isolating authoritative content in a separate repository, we prevent UI modifications from being misinterpreted as knowledge updates or scientific revisions.
3. **Institutional Governance**: This architecture enforces a clear chain of custody for scientific and governance content, ensuring that all authoritative material is versioned and validated independently of presentation concerns.

### Governance Warning

**Any attempt to treat this repository as a source of scientific truth is a governance violation.**

This repository has no authority to:
- Define scientific claims
- Establish governance policies
- Generate institutional references
- Certify research outputs
- Issue authoritative statements

All such authority resides exclusively in designated institutional content repositories (e.g., trizel-site-artifacts).

---

## Repository Contents

- `index.html`: Static landing page for trizel-ai.com

## Deployment

This repository is configured for static site deployment. Changes to `index.html` are reflected on the production website after deployment.
