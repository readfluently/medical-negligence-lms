# Security Policy

## Purpose

The Practitioner-to-Practitioner Medical Negligence LMS is intended to support professional legal and medical education.

Security and confidentiality are therefore important parts of the project.

## Information That Must Never Be Committed to GitHub

Do not commit or upload:

- Passwords
- API keys
- Database credentials
- Authentication secrets
- Supabase service-role keys
- Private encryption keys
- Confidential client information
- Identifiable patient information
- Privileged legal material
- Confidential expert reports
- Confidential medical records
- Internal organisational credentials

## Environment Variables

Sensitive configuration should be stored using environment variables.

For local development, developers should use an environment file such as:

```text
.env.local
```

Environment files containing secrets must not be committed to GitHub.

A safe example file may be committed as:

```text
.env.example
```

The example file should contain variable names but not real passwords, tokens or secret values.

## Legal and Medical Confidentiality

The repository should not be used as a storage location for confidential litigation files.

Training cases should preferably be:

- Fictional
- Properly anonymised
- Publicly available and appropriately licensed
- Or specifically authorised for educational use

## Reporting a Security Vulnerability

If you discover a security vulnerability, do not publish sensitive technical details in a public GitHub issue.

Instead, notify the project owner through an appropriate private communication channel so that the issue can be assessed and addressed responsibly.

## Developer Responsibility

Contributors are responsible for checking their changes before committing them.

Before pushing code, check that the changes do not contain:

- Secrets
- Credentials
- Personal information
- Confidential documents
- Patient information
- Client information

## Security Principle

The project follows the principle:

**If sensitive information is not necessary for the software or educational objective, it should not be stored in the repository.**
