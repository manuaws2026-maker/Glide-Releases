# Privacy Policy

**Last updated: June 22, 2026**

This is a general template and not legal advice; it should be reviewed by a lawyer for the developer's jurisdiction before you rely on it.

---

> ## Summary
>
> - **Glide is local-first.** Your recordings, projects, and exported videos are created and stored only on your Mac. We never upload them and never receive them.
> - **No accounts, no server of ours.** You don't sign up or log in, and there is no Glide backend that holds your content.
> - **AI features are optional and use your own keys.** If you turn them on, your Mac talks directly to the AI provider you chose — not to us — and your keys are stored encrypted on your device.
> - **Analytics are anonymous and opt-out.** No personal information, no recordings, no scripts, no keys — just feature usage and error signals, which you can turn off anytime in the Help panel.
> - **Auto-update talks to GitHub.** The app checks GitHub Releases for updates.

---

## 1. Who this applies to and scope

This Privacy Policy describes how **[Company/Developer Name]** ("we," "us," or "the developer") handles information in connection with **Glide**, a screen-recording video editor for macOS (Apple Silicon, macOS 12 or later) that you download and run on your own Mac.

It applies to your use of the Glide application. It does not apply to third-party services that you separately choose to connect to Glide (for example, Google Gemini, ElevenLabs, or HeyGen) — those are governed by their own privacy policies, described in Section 3.

Glide has no user accounts and no developer-operated backend that receives your content.

---

## 2. Information we do and do not collect

### Local-first by design

Glide runs entirely on your Mac. When you record your screen, edit a project, or export a video, all of that happens locally and the resulting files are saved on your device, under your control.

We do not operate a server that stores your content. We never receive your recordings, your projects, your exports, your scripts, or your briefs. There is nothing for us to "delete from our servers," because we never had it.

We do not ask for your name, email, or any identifying information to run the app, and we do not build a profile of you.

### Anonymous, opt-out product analytics

To understand which features are used and what breaks, Glide includes optional, anonymous product analytics powered by **PostHog** (processed in PostHog's US region). This is disclosed on first run and can be turned off at any time in the app's **Help** panel. When it is off, it stays off.

What this involves:

- **A random local identifier.** Glide generates a random ID on your device so a series of events can be recognized as coming from the same installation. It is not tied to your identity.
- **No location tracking.** IP-based geolocation is disabled and the client IP address is discarded, so events are not tied to your location or identity.

The **only** events we collect are:

- `app_opened` — the app was launched.
- `voiceover_generated` — an AI voiceover was produced.
- `avatar_generated` — an AI avatar was produced.
- `export_completed` — a video export finished, with format, duration, and which feature flags were used.
- `update_downloaded` — an app update was downloaded.
- `app_error` — an error occurred, with a **truncated error message** and no content.

**What is never collected, ever:**

- Your recordings or screenshots
- Your scripts or briefs
- File names or file paths
- Your API keys
- Your name, email, or other identifying information

### Optional crash diagnostics

If you enable it, Glide may send anonymous crash diagnostics so we can find and fix crashes. These reports contain technical diagnostic information about the crash — not your content and not your keys. This is optional and subject to the same opt-out as analytics, in the **Help** panel.

### macOS permissions

Glide asks macOS for the permissions it needs to function: **Screen Recording** to capture your screen, and optionally **Camera**, **Microphone**, or **Speech Recognition** if you use those features. These are standard macOS permissions you grant directly to the app. They are used locally only and do not send anything to us.

---

## 3. Third-party AI services (bring your own key)

Glide's AI features — script writing, AI voiceover, and AI avatar — are optional. To use them, you supply **your own API keys** for the third-party services you want to use.

### How your keys are handled

When you enter a key, Glide stores it **encrypted on your device** using the macOS Keychain (via Electron's `safeStorage`). Your keys are used only to call the third-party service they belong to, directly from your Mac. **We never receive or have access to your keys.**

### How your data flows

When you use an AI feature, the relevant data is sent **from your Mac, directly to the provider you configured** — it does not pass through us:

- For **script writing**, your recording and your brief are sent to **Google Gemini** so it can write the script.
- For **AI voiceover (voice synthesis / voice cloning)**, the script text is sent to **ElevenLabs**.
- For the **AI avatar presenter**, the script text is sent to **HeyGen**.

If you never use the AI features, none of your data is sent to any of these providers.

### Those providers' policies govern that processing

You use these services under your own account, and they bill you directly. Once your data reaches a provider, that provider's own privacy policy and terms govern how they handle it. We encourage you to read them:

- **Google Gemini API** — https://ai.google.dev/gemini-api/terms and https://policies.google.com/privacy
- **ElevenLabs** — https://elevenlabs.io/privacy
- **HeyGen** — https://www.heygen.com/policy

---

## 4. Auto-update and GitHub

Glide checks **GitHub Releases** for updates and may download them. This involves a network request to GitHub. That request is subject to **GitHub's Privacy Statement** (https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). We do not receive any personal information through the update process.

---

## 5. Legal bases for processing (GDPR)

To the extent the EU/UK General Data Protection Regulation applies, our legal bases under Article 6 are:

- **Legitimate interests** (Art. 6(1)(f)) — to operate, maintain, and improve Glide and to diagnose and fix problems, balanced against your rights and limited to the anonymous signals described in Section 2.
- **Consent** (Art. 6(1)(a)) — where required, for analytics and crash diagnostics, which are disclosed and can be turned off at any time in the Help panel.

Because analytics are anonymous and opt-out and we do not otherwise collect personal information, the amount of personal data we process is minimal.

---

## 6. Data retention

Your recordings, projects, and exports live on your Mac and are retained for as long as you keep them; you control their deletion.

Anonymous analytics and crash events are retained only as long as needed for product improvement and diagnostics, after which they are deleted or further aggregated. Because these events are anonymous and contain no content, they cannot be linked back to you.

We do not hold any of your content, so we have no content to retain.

---

## 7. Your rights

### GDPR (EU/UK)

Subject to applicable law, you have the rights to **access**, **rectify**, **erase**, **restrict**, and **object to** processing of your personal data, and to **data portability**. Because we do not maintain accounts or hold your content, and our analytics are anonymous, we typically hold no personal data that we can link to you to act on such a request. You may still contact us using the details in Section 12, and you have the right to lodge a complaint with your local data protection authority.

### CCPA / CPRA (California)

**We do not sell or share your personal information**, and we have no actual knowledge of selling or sharing the personal information of minors under 16. We do not collect the categories of personal information that would require a consumer access or deletion response beyond what is described above. You will not be discriminated against for exercising your privacy rights.

---

## 8. International transfers

If you choose to use an AI feature, your data is sent from your Mac directly to the third-party provider you configured, which may process it in countries outside your own. Those transfers are governed by that provider's policies and safeguards (see Section 3).

The auto-update request to GitHub may likewise be processed outside your country, subject to GitHub's policies (see Section 4). We do not ourselves receive your content, so we do not carry out international transfers of your content.

---

## 9. Children

Glide is not directed to children. It is not intended for use by individuals under 13 (or under 16 where a higher age applies), and we do not knowingly collect personal information from them. Because we do not collect personal information in the ordinary course, there is very little to collect from anyone. If you believe a child has provided personal information in a way that concerns you, please contact us.

---

## 10. Security

Your content stays on your Mac, protected by your device's own security. Your API keys are encrypted at rest using the macOS Keychain via Electron's `safeStorage`. Glide is distributed as a signed and notarized `.dmg` from GitHub Releases, which helps ensure the app you install has not been tampered with. No method of storage or transmission is completely secure, but we design Glide to minimize the data at risk by keeping it on your device.

---

## 11. Changes to this policy

We may update this policy as Glide evolves — for example, if we add a new optional feature. When we do, we will update the "Last updated" date at the top, and significant changes will be noted in the app or in our release notes.

---

## 12. Contact

Questions about privacy? Contact us:

- **[Company/Developer Name]**
- Email: **[contact email]**
- Postal address (if applicable): **[postal address if required]**

Glide runs on macOS 12 or later on Apple Silicon.
