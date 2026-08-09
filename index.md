# Privacy Policy for DMindMap

**Last updated: August 9, 2026**

DMindMap ("the App") is a mobile app that generates mind maps from a topic
you type or a document you upload, using an AI model. This policy explains
what data the App handles and how.

## Summary

DMindMap has no backend server and no account system. The App does not
collect, store, or transmit any of your data to us, the developer. Every
piece of data described below either stays on your device or goes
directly from your device to the AI provider you chose — never through
us.

## What data the App handles

### 1. Your AI provider API key (Bring Your Own Key)

To generate a mind map, you provide your own API key for an AI provider
of your choice (Google Gemini, Anthropic Claude, or DeepSeek). This key
is:

- Stored only on your device, using the operating system's secure
  storage (Android Keystore, via `expo-secure-store`).
- Never sent to us or to any server we operate — the App has no backend.
- Sent only directly from your device to the AI provider's own API, over
  HTTPS, exactly as if you had called that provider's API yourself.

You can delete your stored key at any time from the App's Settings
screen, which removes it permanently from your device.

### 2. The topic you type, or the document you upload

The App generates a mind map from one of two inputs, whichever you use:

- **A topic you type**, or
- **A document you upload** (PDF, .txt, or .md file) from your device's
  file picker.

Whichever you provide is sent directly from your device to the AI
provider's API (Gemini, Claude, or DeepSeek — whichever you selected) to
generate the mind map content. If you upload a document, its full
content (not just a summary) is sent to that provider so it can read the
document's structure and key concepts. This data is subject to that
provider's own privacy policy and terms, not ours:

- Google Gemini: https://policies.google.com/privacy
- Anthropic Claude: https://www.anthropic.com/legal/privacy
- DeepSeek: https://www.deepseek.com/en/privacy-policy

We do not see, log, or store this text or document anywhere, because it
never passes through any system we control. The document is read
directly from where you picked it and is not copied anywhere else on
your device beyond the App's temporary cache, which the operating system
clears automatically.

### 3. Generated mind maps

Mind maps you generate are kept only on your device (and, if you choose
to save an image or export a file, wherever you save it — e.g. your
device's Photos/gallery or Files app). We have no access to them.

### 4. Notifications

If a mind map is still generating when you leave the App, DMindMap may
show a local notification on your device when generation finishes. This
notification is created entirely on your device (via `expo-notifications`)
— no notification token, device identifier, or any other data is sent to
us or to any push notification service. You can deny the notification
permission at any time without affecting the App's core functionality.

## What we do NOT collect

We do not collect: your name, email, location, contacts, device
identifiers, advertising IDs, analytics, or crash reports. The App
contains no analytics SDK and no advertising SDK.

## Third-party services

The App's mind map viewer loads the open-source Mermaid.js rendering
library from a public CDN (jsDelivr) inside an in-app WebView, to draw
the mind map diagram. No personal data is sent to this CDN beyond a
standard request for the library file itself (the same as visiting any
website that uses a CDN).

## Children's privacy

The App is not directed at children under 13 and does not knowingly
collect any data from children, since — per the sections above — it does
not collect data from anyone.

## Changes to this policy

If this policy changes, the "Last updated" date above will change and,
for material changes, we will note it in the App's release notes.

## Contact

Questions about this policy: **doanit1985@gmail.com**
