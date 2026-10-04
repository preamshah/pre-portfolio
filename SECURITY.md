# Security Policy

## Supported Versions

Security reports are considered for the latest version on the repository's default branch.

| Version | Security support |
| --- | --- |
| Latest default branch | Yes |
| Older commits and forks | No guarantee |

## Reporting a Vulnerability

If you discover a potential security vulnerability in this portfolio website, please report it privately rather than publishing exploit details in a public issue.

Use a verified contact method listed on the repository owner's GitHub profile to request a private reporting channel. Include:

- A concise description of the issue and its possible impact
- The affected page, file, or component
- Steps to reproduce the issue
- Relevant screenshots or logs, with personal data and secrets removed
- Any suggested mitigation, if known

**Do not include passwords, access tokens, private keys, session cookies, or other secrets in a report.**

If you cannot find a private contact method, open a public GitHub issue asking how to report a security concern securely. Do not include exploit code or sensitive details in that issue.

## Response and Disclosure

The maintainer will make a reasonable effort to review reports, confirm reproducible issues, and communicate the status of remediation. Response and remediation times are not guaranteed.

Please allow a reasonable opportunity to investigate and address a vulnerability before publicly disclosing technical details. This policy does not establish a bug bounty program or a guaranteed service level.

## Security Considerations

Based on the supplied `index.html`, this project appears to be a static front-end website. Consider the following:

- **Secrets and credentials:** Never commit passwords, API secrets, private keys, access tokens, hosting credentials, or `.env` files.
- **Public assets:** Treat every committed file as public, including résumé PDFs, images, analytics identifiers, and site-verification tokens.
- **Third-party scripts:** The page loads libraries and fonts from external CDNs. Keep dependencies under review and load only resources you trust. Consider Subresource Integrity where suitable and supported.
- **External links:** Review links that open new tabs and use safe link handling where appropriate.
- **Analytics and privacy:** Verify that analytics configuration is yours and review applicable privacy disclosure and consent requirements.
- **File paths:** Check that all local assets resolve correctly and do not expose files that should remain private.
- **Maintenance:** Periodically review externally loaded libraries and update outdated versions when appropriate.

## Scope

This policy covers the portfolio website and files maintained in this repository. Third-party services, libraries, and websites are outside the repository owner's direct control; report issues to their respective maintainers where appropriate.
