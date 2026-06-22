# Privacy Policy

**Last updated: June 22, 2026**

This is a general template, not legal advice; have a lawyer review it for your jurisdiction before you rely on it.

---

> ## Summary
>
> - **Glide is local‑first.** Your recordings, projects, and exported videos are created and stored only on your Mac. Glide is designed so we never upload or receive them.
> - **No accounts, no server of ours.** You don't sign up or log in, and there is no Glide backend that holds your content.
> - **AI features are optional and use your own keys.** If you turn them on, your Mac talks directly to the AI provider you chose — not to us — and your keys are stored encrypted on your device.
> - **Usage analytics are pseudonymous and easy to turn off.** No name, no recordings, no scripts, no keys — just feature‑usage and error signals tied to a random local ID, which you can turn off anytime in **Help → Privacy & analytics**.
> - **Auto‑update talks to GitHub.** The app checks GitHub Releases for updates.

---

## Contents
1. Scope · 2. What we do and don't collect · 3. Third‑party AI services · 4. Auto‑update and GitHub · 5. Legal bases (GDPR) · 6. Retention · 7. Your rights · 8. International transfers · 9. Children · 10. Security · 11. Local storage · 12. Changes · 13. Contact

## 1. Scope

This Privacy Policy describes how **Manu Mehrotra, an individual** ("we," "us," or "the developer") handles information in connection with **Glide**, a screen‑recording video editor for macOS (Apple Silicon, macOS 12 or later) that you download and run on your own Mac.

It covers the Glide application. It does not cover third‑party services you separately choose to connect (Google Gemini, ElevenLabs, HeyGen), which are governed by their own policies (Section 3). Glide has no user accounts and no developer‑operated backend that receives your content.

## 2. What we do and don't collect

### Local‑first by design

Glide runs on your Mac. Recording, editing, and exporting all happen locally, and the files are saved on your device under your control. We do not operate a server that stores your content, and Glide is designed so that we do not receive your recordings, projects, exports, scripts, or briefs. We don't ask for your name or email to run the app, and we don't build a profile of you.

### Pseudonymous usage analytics (on by default, easy to turn off)

To understand which features are used and what breaks, Glide includes product analytics powered by **PostHog**, which acts as our data processor and processes these events in the **United States** under a data‑processing agreement. This is disclosed on first run. **In the EU and UK it is off until you choose to turn it on (opt‑in); elsewhere it is on by default and you can turn it off at any time (opt‑out)** — both in **Help → Privacy & analytics**. When it's off, it stays off.

What this involves:

- **A random local identifier** generated on your device, so a series of events can be recognized as coming from the same installation. It is **not tied to your identity** — but because it is a persistent identifier, we treat it as **pseudonymous personal data**, not strictly anonymous, and minimize it accordingly.
- **No location tracking.** IP‑based geolocation is disabled and the client IP is not stored, so events are not tied to your location.

The **only** events collected are:

- `app_opened` — the app was launched.
- `voiceover_generated` — an AI voiceover was produced.
- `avatar_generated` — an AI avatar was produced.
- `export_completed` — an export finished, with format, duration, and which features were used.
- `update_downloaded` — an app update was downloaded.
- `app_error` — an error occurred, with a **truncated error message** and no content.

**By design, we do not collect:** your recordings or screenshots; your scripts or briefs; file names or paths; your API keys; or your name, email, or other identifying information. (Error messages are truncated and scrubbed of content on a best‑effort basis.)

### Optional crash diagnostics

Crash diagnostics are **off unless you enable them.** If enabled, they may send technical diagnostic information about a crash — not your content and not your keys — and are subject to the same controls in **Help → Privacy & analytics**.

### macOS permissions

Glide asks macOS for **Screen Recording**, and optionally **Camera**, **Microphone**, or **Speech Recognition** if you use those features. These are standard permissions you grant to the app; they are used locally only and don't send anything to us.

## 3. Third‑party AI services (bring your own key)

Glide's AI features — script writing, AI voiceover/voice cloning, and the AI avatar — are optional. To use them, you supply **your own API keys**.

**How your keys are handled.** When you enter a key, Glide stores it **encrypted on your device** using the macOS Keychain (via Electron's `safeStorage`), where supported by your system. Keys are used only to call the service they belong to, directly from your Mac. **We never receive or have access to your keys.**

**How your data flows.** When you use an AI feature, the relevant data is sent **from your Mac directly to the provider you configured — it does not pass through us:**

- **Script writing** → your recording and brief are sent to **Google Gemini**.
- **AI voiceover / voice cloning** → the script text (and, for cloning, the voice sample you provide) is sent to **ElevenLabs**.
- **AI avatar presenter** → the script text is sent to **HeyGen**.

If you never use the AI features, none of your data is sent to any of these providers. You use these services under your own account, they bill you directly, and once your data reaches a provider, that provider's policy and terms govern it. For these direct calls you act on your own account; we are neither controller nor processor of that data. We encourage you to read their policies:

- **Google Gemini API** — https://ai.google.dev/gemini-api/terms and https://policies.google.com/privacy
- **ElevenLabs** — https://elevenlabs.io/privacy
- **HeyGen** — https://www.heygen.com/policy

## 4. Auto‑update and GitHub

Glide checks **GitHub Releases** for updates and may download them, which involves a network request to GitHub, subject to **GitHub's Privacy Statement** (https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). We do not receive personal information through the update process.

## 5. Legal bases for processing (GDPR/UK GDPR)

To the extent the EU/UK GDPR applies: for users in the **EU/UK**, where analytics are **off until you opt in**, our legal basis is your **consent** (Art. 6(1)(a)), which you can withdraw at any time in **Help → Privacy & analytics**. For users elsewhere, we rely on our **legitimate interest** (Art. 6(1)(f)) in maintaining, securing, and improving Glide and diagnosing problems — limited to the minimal pseudonymous signals in Section 2 — and you can object or turn it off at any time in the same place. We do not use this data for advertising or profiling, and we collect no special‑category data.

## 6. Retention

Your recordings, projects, and exports live on your Mac for as long as you keep them; you control their deletion. Pseudonymous analytics and crash events are retained for up to **12 months** and then deleted or aggregated; you can adjust retention in the PostHog project settings. We hold none of your content, so there is no content for us to retain.

## 7. Your rights

**GDPR (EU/UK).** Subject to applicable law, you have the rights to **access, rectify, erase, restrict, object to** processing, and to **data portability**. Because we keep no accounts and hold no content, and our analytics are pseudonymous, we usually cannot link a request to a specific person without more information. If you want the events from your installation deleted, send us the random identifier (you can turn analytics off to stop new events) and we will delete the associated events. We respond within the timeframes required by law and you may complain to your local data‑protection authority.

**CCPA / CPRA (California).** The only category of personal information we collect is **internet or other electronic network activity** (limited app‑usage and error events tied to a random local identifier). We collect it to maintain and improve Glide, retain it as in Section 6, and **do not sell or share it** (as "sell" and "share" are defined under the CPRA), do not use it for cross‑context behavioral advertising, and collect no sensitive personal information. You will not be discriminated against for exercising your rights.

## 8. International transfers

If you use an AI feature, your data goes from your Mac directly to the provider you configured, which may process it outside your country under that provider's safeguards (Section 3). Our analytics provider (PostHog) processes pseudonymous usage events in the **United States**; where this involves transferring EU/UK personal data, it is covered by appropriate safeguards (such as Standard Contractual Clauses / the UK Addendum or a recognized framework). We do not ourselves transfer your **content** internationally, because we never receive it.

## 9. Children

Glide is not directed to children and is not intended for anyone **under 16**. We do not knowingly collect personal information from children. Because we don't collect personal information in the ordinary course, there is little to collect from anyone. If you believe a child has provided information in a way that concerns you, contact us.

## 10. Security

Your content stays on your Mac, protected by your device's own security. Your API keys are encrypted at rest using the macOS Keychain via Electron's `safeStorage`, where supported. Glide is distributed as a signed and notarized `.dmg` from GitHub Releases, which helps ensure the app you install hasn't been tampered with. No method of storage or transmission is completely secure, but we minimize the data at risk by keeping it on your device. In the unlikely event of a personal‑data breach affecting analytics data, we will notify the relevant authority and affected users where required by law.

## 11. Local storage

Glide does not use web cookies or advertising identifiers. It stores your app settings and — if analytics are on — a random local identifier on your Mac. That's the only on‑device storage used for these purposes.

## 12. Changes

We may update this policy as Glide evolves. We'll update the "Last updated" date above, note significant changes in the app or release notes, and — if our practices materially change — update the in‑app disclosure before the change takes effect.

## 13. Contact

- **Manu Mehrotra**
- Email: **septembermanu@gmail.com**

Glide runs on macOS 12 or later on Apple Silicon.
