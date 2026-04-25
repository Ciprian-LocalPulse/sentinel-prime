# Security Policy

## Overview

Sentinel Prime is a public proof-of-concept cybersecurity dashboard UI kit with a separate Private Enterprise Edition.

This policy applies only to the public repository and public preview materials. It does not grant access to operational security logic, telemetry pipelines, detection rules, client environments, token generation methods, private playbooks, prompts, API keys, production connectors, customer data, or commercial implementation details.

## Supported Scope

Security reports are welcome for:

- exposed secrets, credentials, keys, or tokens
- accidental disclosure of private implementation detail
- unsafe public documentation
- unsafe public demo behavior
- repository integrity concerns
- misleading public security, compliance, or product claims that could create buyer or user risk
- brand impersonation or malicious mirrors involving this repository

Out of scope:

- requests for telemetry pipelines or detection rules
- requests for operational threat intelligence feeds
- requests for production security logic
- requests for token generation methods
- requests for private playbooks, prompts, or client environment details
- requests for customer, analyst, endpoint, or incident data
- testing against third-party systems, accounts, or infrastructure
- social engineering, phishing, spam, or denial-of-service activity

## Reporting a Vulnerability

Do not open a public GitHub issue for security vulnerabilities.

Use a private channel:

- Security inquiry: contact@localpulse.pro
- Private briefing: https://cal.com/ciprian-stefan-plesca

Use the subject line:

```text
[SECURITY] Sentinel Prime - <short summary>
```

Please include:

- affected file or URL
- clear description of the issue
- reproduction steps if applicable
- impact assessment
- whether any sensitive material appears exposed
- suggested remediation, if available
- your preferred contact method

## Responsible Disclosure Expectations

Researchers and reviewers must:

- avoid public disclosure before review
- avoid testing systems they do not own or control
- avoid accessing, modifying, deleting, or exfiltrating data
- avoid posting live secrets in public issues, pull requests, or discussions
- keep reports concise, factual, and confidential

The maintainer will make a good-faith effort to review legitimate reports, validate impact, and remediate public-repository issues in a timely manner.

## Production Security Boundary

Sentinel Prime is not production security software. Do not submit real telemetry, endpoint data, incident data, customer data, credentials, detection content, or threat intelligence data to this repository.

If you believe sensitive security data has been exposed, report it privately immediately and do not copy it into public channels.

## Private Enterprise Boundary

Security review of the Private Enterprise Edition, if requested by an authorized buyer or partner, must be handled through a separate private diligence process under written agreement.

Private package access is not available through public issues, pull requests, or security reports.

## No Warranty

This public repository is provided for evaluation and discussion only. It is not a security certification, compliance certification, production readiness attestation, threat-detection validation, legal opinion, or managed security service.

