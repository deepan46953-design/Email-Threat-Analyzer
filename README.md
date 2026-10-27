# Email Threat Analyzer

## Overview
Email Threat Analyzer is a security utility designed to inspect incoming emails for potential security risks, including phishing attempts, spoofed senders, and malicious attachments or URLs.

## Key Features
- **Header Parsing:** Analyzes email authentication headers (SPF, DKIM, DMARC) to verify sender legitimacy.
- **URL & Domain Analysis:** Extracts embedded links and checks domain reputation against known threat lists.
- **Attachment Inspection:** Scans attached files for malicious extensions and computes file hashes for signature matching.
- **Threat Scoring:** Provides a consolidated risk assessment to help analysts quickly triage suspicious emails.
