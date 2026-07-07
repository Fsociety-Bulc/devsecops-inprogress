# Third-Party Software Supply Chain Governance Framework

A single-page, self-contained HTML deliverable that presents an enterprise
governance framework for validating third-party software, verifying vendor
security claims without source-code access, and governing trust across a
Red Hat OpenShift platform.

## Files

- `index.html` — the current, published version of the framework document.
- `indexv1.html` — an earlier iteration, retained for reference.
- `index2.html` — a working copy; not the published version.

## Live site

Deployed via Vercel: https://devsecops-inprogress.vercel.app/

## Recent updates

- Added an "Evidence Concepts Explained" plain-language guide beneath the
  "Five Claims, Mapped to Verifiable Evidence" table.
- Added verified, machine-readable file samples: CycloneDX (JSON), SPDX
  (tag-value and YAML), OpenVEX, and an in-toto config attestation.
- Aligned tool references to the project stack (OpenShift, Sonatype Nexus +
  Repository Firewall, Prisma Cloud, Trivy, HashiCorp Vault, Cosign/Sigstore).
- Fact-checked technical claims against primary sources (OpenVEX, Trivy,
  CycloneDX, and SPDX specifications).
