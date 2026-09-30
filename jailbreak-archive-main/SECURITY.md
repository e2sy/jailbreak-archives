# Security Policy

## Scope

This repository is maintained strictly for **educational, research, and defensive analysis** purposes — documenting adversarial prompt engineering techniques against Large Language Models for AI safety research and red-teaming.

This policy covers:
- Vulnerabilities in this repository's contents or structure
- Responsible disclosure of new adversarial prompt techniques against vendor LLM products
- Reports of misuse of repository content

## Reporting a Vulnerability

### Repository / Project Security

If you discover a security issue with the repository itself (e.g., exposed credentials, malicious content, supply-chain concerns), please **do not** open a public issue. Instead, report it privately:

1. Open a private security advisory: **Security tab → Report a vulnerability** on the GitHub repo page.
2. Include a clear description, reproduction steps, and impact assessment.

You will receive an acknowledgment within **72 hours** and a status update within **7 days**.

### Adversarial Prompt / LLM Vulnerability Disclosure

For new jailbreak / adversarial prompt techniques discovered against vendor LLM products:

1. **Coordinate with the affected vendor FIRST.** Most major LLM providers maintain a bug bounty or responsible-disclosure channel:
   - OpenAI: <https://bugcrowd.com/openai>
   - Anthropic: <https://www.anthropic.com/legal/security>
   - Google DeepMind: <https://bughunters.google.com>
   - DeepSeek: see their responsible disclosure policy
2. Wait for remediation or coordinated public disclosure timeline before submitting the entry here.
3. Submit the archived entry only after the vendor has confirmed remediation or agreed to disclosure.

Entries that bypass active, undisclosed vendor vulnerabilities will **not** be accepted.

## Acceptable Use

Repository content must not be used to:
- Attack systems you do not own or lack explicit authorization to test
- Facilitate cheating, fraud, abuse, or harm against end users
- Violate any vendor's Terms of Service

Maintainers reserve the right to remove any entry that fails these criteria.

## Disclosure Timeline

| Stage | SLA |
|:------|:---|
| Acknowledgment of report | 72 hours |
| Initial assessment | 7 days |
| Status update / remediation plan | 30 days |
| Public disclosure (if applicable) | After vendor remediation or coordinated timeline |
