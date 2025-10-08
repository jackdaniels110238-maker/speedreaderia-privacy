# Privacy Policy

Last Updated: October 4, 2025

## Overview

Speed Reader IA is committed to protecting user privacy. This policy explains how the extension handles information.

## Data Collection

This extension does not collect, store, or transmit personal information by default. However, if a user enables integration with an external service (for example, Google Gemini) and provides an API key, the selected content (text, images or code) may be sent directly from the user's browser to that third‑party service for processing. Such transmissions only occur with explicit user action and consent.

### What We Do Not Collect
- Personal identification information
- Browsing history or activity
- Usage analytics or metrics
- Location data
- Any data transmitted to third-party servers

## Local Storage

The extension stores data locally on your device only:

### User Preferences
- Reading speed and voice settings
- Interface language preference
- History retention configuration

### API Key
- The API key provided by the user is stored in Chrome storage (either sync or local, depending on user settings).  
- The user can remove the API key at any time from the extension settings.  
- The API key is used only from the user's browser to communicate directly with the selected provider (for example, Google Gemini) and is not forwarded to any servers operated by this extension.

### Consultation History
- AI query results (image descriptions, code analysis, custom queries)
- Stored in Chrome local storage
- User-controllable deletion and export

## Third-Party Services

### Google Gemini API
AI features may send selected content (text, images, or code) directly from the user's browser to Google Gemini only when the user explicitly enables that integration and enters their own API key. The API key is stored in Chrome storage (sync or local, according to user settings) and is used solely from the user's browser to authenticate requests to the provider; the extension does not forward stored API keys to external servers.

Use of Google Gemini is subject to the provider's terms and privacy policy: https://policies.google.com/privacy

- What may be sent: selected text, images, or code for analysis (only with explicit user action).
- User control: the integration is opt‑in and the user can remove the API key at any time via the extension settings.

### Web Speech API (Text-to-Speech)
- Uses the browser's native Web Speech API for text-to-speech functionality.
- All processing occurs locally in the user's device using browser-provided voices.
- Some browser-provided voices may rely on remote services managed by the browser vendor; when that occurs, audio synthesis is performed by the browser/provider and is subject to the provider's privacy policy.
- The extension does not transmit text or audio data to external servers for TTS purposes.

## Data Security

- API keys and user preferences are stored in Chrome storage (sync or local) and can be removed by the user at any time.  
- This extension does not operate external servers for user data. All processing is performed in the user's browser unless the user explicitly enables an external API.  
- Users are responsible for the security of any API keys they choose to enter. The extension does not transmit stored keys to third parties.

## User Control

Users maintain complete control:
- Remove API key: open extension settings → Privacy / Integrations → Remove API key.
- Delete history: open extension settings → History → Clear history.
- Uninstalling the extension removes local data stored by the extension.
- The user may also export or delete stored consultation history via Settings → History → Export / Clear.

## Permissions Justification

- **activeTab**: Access and interact with the current tab when the user activates the extension (via icon, shortcut, or context menu).  
- **storage**: Persist user preferences locally (voice selection, playback speed, API key, UI settings).  
- **tabs**: Synchronize settings and commands across open tabs when the user changes configuration. Not used to collect browsing history or data.  
- **host_permissions**: Limited to endpoints required for optional external API calls (Google Gemini) and to pages where the user activates the extension.

These permissions do not enable data collection or external transmission beyond user-initiated Gemini API requests.

## Children's Privacy

This extension does not target or knowingly collect information from users under 13. Parental consent recommended for use of AI features requiring API key.

## Policy Updates

This policy may be updated periodically. Material changes will be reflected in the "Last Updated" date.

## Data Retention

- Local data retained until user deletion or extension uninstall
- No server-side data retention

## User Rights

Users may:
- Access data stored locally on their device
- Delete data via extension settings or uninstall
- Export history through built-in export feature

## Compliance

This extension is designed to follow applicable laws and Chrome Web Store policies (for example, GDPR and CCPA). No formal audit or certification (for example, SOC 2) is claimed here unless supporting documentation is provided.

## Contact

For privacy concerns or questions, please open an issue in the project repository.

---

This privacy policy applies to Speed Reader IA Chrome extension version 1.0.0 and later. A publicly accessible copy of this policy will be available at the URL provided in the Chrome Web Store listing.

This extension complies with:
- Chrome Web Store policies
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

## Legal Basis for Processing

We process data based on:
- **Consent**: You choose to use AI features
- **Legitimate Interest**: Providing requested services
- **Local Processing**: Most features don't involve external processing

---

## Compliance

This extension is designed to follow applicable laws and Chrome Web Store policies (for example, GDPR and CCPA). No formal audit or certification (for example, SOC 2) is claimed here unless supporting documentation is provided.

**Summary**: We don't collect your data. Everything stays on your device. You control everything.
