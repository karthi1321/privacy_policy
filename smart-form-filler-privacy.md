# Smart Form Filler — Privacy Policy
_Last updated: 2025-08-23_

## No data collection
Smart Form Filler does **not collect, transmit, sell, or share** personal data.  
The extension runs only when you click its popup and operates on the current page.

## Local storage only
Your profiles and preferences are stored **locally** in your browser using `chrome.storage.local`.  
They never leave your device unless you export or share them.

## How it works
- On user action (**Fill**, **Auto-Fill**, **Fake**, **Capture → Profile**), a short script is injected into the active tab to read/write form fields.
- The extension skips security-sensitive elements (hidden/disabled/readonly inputs and CAPTCHAs).
- No analytics, no advertising, no third-party SDKs.

## Permissions
- `activeTab` — temporary access to the current tab after a user gesture.
- `scripting` — injects the script that fills inputs when you click.
- `storage` — saves your profiles locally.

## Contact
Questions? Email **nrk.karthicknrk@gmail.com**.
