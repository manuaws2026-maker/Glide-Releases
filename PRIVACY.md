# Privacy Policy

**Last updated: June 21, 2026**

> **Heads up:** This is a starting template — have a lawyer review it before relying on it.

Glide is a screen‑recording video editor that runs on your Mac. This policy explains, in plain English, what happens to your data when you use it. The short version: **Glide is local‑first, and your recordings never leave your machine unless you choose to use an optional AI feature.**

---

## The short version

- **Everything lives on your Mac.** Your recordings, projects, and exported videos stay on your device. We never upload them, and we never receive them.
- **There are no accounts and no server of ours.** You don't sign up, you don't log in, and there's no Glide cloud holding your stuff.
- **AI features are optional and use your own keys.** If you turn them on, your machine talks directly to the AI provider you chose — not to us.
- **Analytics and crash reports are anonymous and easy to turn off.** No personal information, no account, and you can switch them off anytime in Settings.

---

## Your recordings stay on your Mac

Glide runs entirely on your computer. When you record your screen, edit a project, or export a video, all of that happens locally. Those files are saved on your Mac, under your control.

We don't have a server that stores your content. We never see your recordings, your projects, or your exports. There's nothing to "delete from our servers" because we never had it in the first place.

---

## No accounts, no tracking of who you are

You don't create an account to use Glide, and we don't ask for your name, email, or any identifying information to run the app. We don't build a profile of you.

---

## Optional AI features (bring your own key)

Glide's AI voiceover and AI avatar are optional. To use them, you paste in **your own API keys** for the third‑party services you want to use:

- **Google Gemini** — watches your recording and writes the script.
- **ElevenLabs** — turns the script into a lifelike AI voice.
- **HeyGen** — turns the script into an AI avatar presenter.

A few important things about how this works:

### Your keys are stored encrypted, on your Mac

When you paste a key, Glide stores it **encrypted on your device** using the macOS Keychain (via Electron's `safeStorage`). The keys never leave your Mac except to authenticate directly with the service they belong to. **We never see or receive your keys.**

### Your machine talks to the provider directly

When you use an AI feature, the relevant data is sent **from your Mac, directly to the provider you configured** — it does not pass through us:

- For the **AI voiceover**, your recording and your short brief are sent to **Google Gemini** so it can write the script.
- For **voice synthesis**, the script text is sent to **ElevenLabs**.
- For the **AI avatar**, the script text is sent to **HeyGen** for synthesis.

### Those providers' terms govern that data

Once your data reaches one of these services, that provider's privacy policy and terms apply to how they handle it. You're using your own account with them, and they bill you directly. We'd encourage you to read their policies:

- **Google Gemini API** — https://ai.google.dev/gemini-api/terms and https://policies.google.com/privacy
- **ElevenLabs** — https://elevenlabs.io/privacy
- **HeyGen** — https://www.heygen.com/policy

If you never use the AI features, none of your data is sent to any of these providers.

---

## Anonymous product analytics (optional, opt‑out)

To understand which features people use and to find and fix problems, Glide includes optional, anonymous product analytics powered by **PostHog**. Here's exactly what that means:

- **No personally identifiable information.** We don't collect your name, email, or anything that identifies you.
- **No account.** Analytics aren't tied to any identity.
- **A random local identifier.** Glide generates a random ID on your device so we can tell that a series of events came from the same install — it isn't tied to who you are.
- **Feature usage and problems only.** We use it to learn things like "which export formats get used" or "where does something break," so we can improve the app.
- **Never your content.** We never send the content of your recordings, your scripts, or your API keys to analytics. Ever.

This is **disclosed on first run**, and it's **opt‑out** — you can turn it off anytime in **Settings**, and it stays off.

---

## Anonymous crash reporting (optional, opt‑out)

If enabled, Glide may send anonymous crash diagnostics through **Sentry** so we can spot and fix crashes. These reports contain technical diagnostic information about the crash, not your content or your keys. Like analytics, this is optional and can be turned off in **Settings**.

---

## macOS permissions

Glide asks macOS for the permissions it needs to do its job — **Screen Recording** to capture your screen, and **Camera**, **Microphone**, or **Speech Recognition** only if you use those features. These are standard macOS permissions you grant directly to the app on your own Mac. They let Glide function locally; they don't send anything to us.

---

## Children

Glide isn't directed at children and doesn't knowingly collect any information from them. (Since we don't collect personal information at all, there's very little to collect from anyone.)

---

## Changes to this policy

We may update this policy as Glide evolves — for example, if we add a new optional feature. When we do, we'll change the "Last updated" date at the top. Significant changes will be noted in the app or our release notes.

---

## Contact

Questions about privacy? Reach out and we'll be glad to help.

**Requirements:** Glide runs on macOS 12+ on Apple Silicon.
