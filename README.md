# THOT Logged In Until Automator

A Microsoft Edge browser extension that automates the daily updating of a user's Salesforce **Logged In Until** setting.

## Overview

THOT Logged In Until Automator helps Salesforce users maintain their availability by automatically updating the `Available_Until__c` field according to their configured schedule.

The extension uses the user's existing authenticated Salesforce browser session and communicates directly with the configured Salesforce environment.

## Features

- Automatically updates the Salesforce Logged In Until setting.
- Supports configurable Salesforce domains.
- Supports configurable target time and timezone.
- Supports daily scheduled execution.
- Checks Out-of-Office (OOO) status before performing updates.
- Provides browser notifications for update results and errors.
- Supports multiple user interface languages.

## Privacy

This extension accesses Salesforce user information and session information solely to provide its intended functionality.

For details about information access, usage, storage, and protection, please refer to our:

**[Privacy Policy](https://<github-username>.github.io/edge-extension-privacy/)**

## Repository Structure

```text
edge-extension-privacy/
│
├── index.md       # Privacy Policy published through GitHub Pages
└── README.md      # Project documentation
```

## Disclaimer

This extension is an independent utility and is not affiliated with, endorsed by, or officially supported by Salesforce or Microsoft.

Salesforce is a trademark of Salesforce, Inc.

## Contact

For questions or concerns regarding this extension or its privacy practices, please contact:

**Developer:** Brent Li

**Email:** litbyte@gmail.com
