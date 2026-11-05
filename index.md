# THOT Logged In Until Automator – Privacy Policy

**Last Updated: November 5, 2026**

## 1. Introduction

THOT Logged In Until Automator ("the Extension") is a Microsoft Edge browser extension designed to automate the daily updating of a user's Salesforce "Logged In Until" setting.

This Privacy Policy explains what information the Extension accesses, how that information is used, and how it is handled.

The Extension is designed to operate directly within the user's browser and communicate with the user's configured Salesforce environment.

## 2. Information We Access

To provide its functionality, the Extension accesses the following information:

**2.1 Salesforce Session Information**

- The Salesforce session cookie (`sid`) associated with the user's configured Salesforce domain.
- The session cookie is used to authenticate API requests to Salesforce.
- The Extension does not intentionally store or transmit this session cookie to the Extension developer or unrelated third parties.

**2.2 Salesforce User Information**

The Extension retrieves the following information about the currently authenticated Salesforce user:

- Salesforce User ID.
- Username.
- Out-of-Office (OOO) start date.
- Out-of-Office (OOO) end date.
- Logged In Until (`Available_Until__c`) value.

This information is accessed solely to determine whether an update is necessary and whether the user is currently out of office.

**2.3 Extension Configuration**

The Extension stores the following user-configurable settings:

- Salesforce domain.
- Target timezone.
- Target Logged In Until time.
- Daily scheduled execution time.
- User interface language preference.

These settings are stored using the browser's extension synchronization storage (`chrome.storage.sync`) and may be synchronized through the browser's synchronization service, subject to the user's browser account and synchronization settings.

## 3. How We Use Information

The Extension uses the accessed information exclusively to provide its intended functionality.

Specifically, it:

- Identifies the currently authenticated Salesforce user.
- Checks the user's current Logged In Until value.
- Checks the user's Out-of-Office status.
- Skips the update when the user is currently out of office.
- Updates the user's Logged In Until (`Available_Until__c`) field when the existing value is missing or has expired.
- Executes the update automatically according to the user's configured schedule.
- Displays notifications to inform the user about successful updates, skipped operations, or errors.

The Extension does not use Salesforce information for advertising, user profiling, or unrelated purposes.

## 4. Information Storage and Transmission

The Extension is designed to process Salesforce information directly within the browser.

- Salesforce user information is retrieved directly from the configured Salesforce environment through its REST API.
- The Salesforce session cookie is used to authenticate requests to Salesforce and is not intentionally stored in the Extension's own persistent storage.
- The Extension does not operate a separate developer-controlled backend server for collecting or storing Salesforce user information.
- Extension configuration settings are stored using browser synchronization storage and may be synchronized according to the browser's synchronization functionality and settings.
- API communications with Salesforce use HTTPS.

The Extension does not intentionally transmit Salesforce user information to the Extension developer or unrelated external services.

## 5. Information Sharing

The Extension does not sell, rent, or share users' personal information with advertisers or unrelated third parties.

Information is communicated to Salesforce only as necessary to retrieve and update the user's Salesforce account information.

Configuration settings may be handled by the browser's synchronization service when synchronization is enabled.

## 6. Data Retention

The Extension does not maintain an independent database or backend storage containing Salesforce user information.

- Salesforce session information is accessed for API authentication and is not intentionally persisted by the Extension.
- Salesforce user information is processed as needed to perform the scheduled update.
- Extension configuration settings remain in browser extension storage until they are changed or removed, subject to browser synchronization behavior.

## 7. Data Security

The Extension uses HTTPS when communicating with Salesforce.

It relies on the user's existing Salesforce authentication session and does not require users to provide their Salesforce passwords directly to the Extension.

Users should maintain the security of their browser profile and Salesforce account, including protecting their authenticated browser sessions.

## 8. User Control

Users can control the Extension's behavior through its configuration page.

Users can:

- Configure or change the Salesforce domain.
- Change the target timezone and Logged In Until time.
- Change the daily execution schedule.
- Disable or uninstall the Extension at any time.

Users can also manage their Salesforce account information through their organization's Salesforce environment.

## 9. Children's Privacy

The Extension is intended for business and professional use. It is not designed to collect personal information from children.

## 10. Changes to This Privacy Policy

This Privacy Policy may be updated to reflect changes in the Extension's functionality or data handling practices.

The latest version will be published at this URL.

## 11. Contact Information

For questions, concerns, or requests regarding this Privacy Policy, please contact:

**Extension Name:** THOT Logged In Until Automator

**Developer:** [Brent Li]

**Contact Email:** [li.bitao@hotmail.com]