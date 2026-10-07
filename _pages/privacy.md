---
permalink: /privacy/
title: Privacy Policy
---

{% assign app = site.oauth_app %}

**Effective date:** {{ app.effective_date }}

This Privacy Policy describes how **{{ app.name }}** ("the App", "we", "us") collects, uses, stores and shares information when you use the App and sign in with your Google account. The App is developed and operated by {{ site.author.name }}.

By using the App you agree to the practices described in this policy.

## Information we access

When you sign in with Google and grant permission, the App may access the following Google user data, limited to the scopes you explicitly approve on the Google consent screen:

- **Basic profile information** — your name, email address and profile picture, used to identify your account.
- **Google Drive** — files and folders that you choose to open with the App or that the App creates.
- **Google Sheets** — spreadsheets that you choose to work with in the App.
- **Google Docs** — documents that you choose to work with in the App.

The App does not request access to any other Google services.

## How we use information

Google user data is used **only** to provide and improve the user-facing features of the App that you request, for example reading, creating or updating your documents and spreadsheets at your direction. We do not use Google user data for:

- advertising, including personalized, retargeted or interest-based ads;
- selling to data brokers, information resellers or any other third party;
- determining creditworthiness or for lending purposes;
- training general-purpose artificial intelligence or machine learning models.

## Compliance with Google API Services User Data Policy

The App's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## How we store and protect information

- OAuth access and refresh tokens are stored securely and used only to make requests to Google APIs on your behalf.
- The contents of your Drive files, Sheets and Docs are processed only as needed to perform the action you requested and are not retained longer than necessary for that purpose.
- Data is transmitted over encrypted connections (HTTPS/TLS).
- Humans do not read your Google user data unless you give explicit consent for a specific item (for example, for support), it is necessary for security purposes such as investigating abuse, or it is required by law.

## Sharing of information

We do not sell, rent or trade your personal information. We share Google user data only:

- with your explicit consent;
- when required by applicable law, regulation or legal process;
- to protect the security or integrity of the App and its users.

## Data retention and deletion

We keep your information only as long as your account is active or as needed to provide the App. You can at any time:

- revoke the App's access to your Google account at [myaccount.google.com/permissions](https://myaccount.google.com/permissions);
- request deletion of any data associated with your account by emailing [{{ app.contact_email }}](mailto:{{ app.contact_email }}).

After a deletion request we remove your data within 30 days, unless we are required by law to keep it.

## Children's privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from them.

## Changes to this policy

We may update this Privacy Policy from time to time. Changes take effect when they are published on this page, and the effective date above will be updated.

## Contact

If you have questions about this Privacy Policy, contact us at [{{ app.contact_email }}](mailto:{{ app.contact_email }}).
