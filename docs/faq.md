# FAQ

## What do I need to run Glide?
macOS 12 or newer on an Apple Silicon Mac. Download the `.dmg` from the [latest release](https://github.com/manuaws2026-maker/Glide-Releases/releases/latest), open it, and drag Glide into Applications.

## Does Glide need any permissions?
Yes — the usual macOS recording permissions:
- **Screen Recording** (required to capture your screen)
- **Camera** and **Microphone** (only if you record them)
- **Speech Recognition** (only for auto‑captions)

macOS prompts you the first time. If you ever miss a prompt, enable them under **System Settings → Privacy & Security**.

## Is my data private?
Yes. Glide runs entirely on your Mac. Recordings, projects, and exports stay local. The only time anything leaves your machine is if you use the optional AI features — the voiceover sends your recording and brief to the AI services you’ve configured; the AI avatar sends your script text to HeyGen.

## What do I need for the AI voiceover?
It’s optional. To use it you bring your own API keys:
- **Google Gemini** — writes the script (it watches your recording).
- **ElevenLabs** — speaks the script in a lifelike voice.

You paste these once; they’re stored **encrypted on your Mac** and used only to call those services, billed to your own accounts. You can also skip AI entirely and record narration with your own voice.

## What do I need for the AI avatar?
The AI avatar presenter uses your own **HeyGen** API key. Two things to know:
- Your HeyGen account needs **API credits** — these are a **separate wallet** from a HeyGen studio/subscription plan. Enable them under **Settings → API** at app.heygen.com.
- It’s pay‑as‑you‑go (~$3–4 per minute of avatar video), billed to your HeyGen account.

Paste the key once in the avatar window; it’s stored **encrypted on your Mac** and used only to call HeyGen. Glide lets you choose a voiceover **or** an avatar upfront, so you don’t spend voice credits if you’d rather use the avatar.

## My HeyGen avatar fails with “insufficient credit” — why?
HeyGen separates **studio credits** (the web app) from **API credits** (what Glide and any API use). A studio subscription doesn’t fund the API. Add **API credits** under Settings → API at app.heygen.com, then try again.

## What formats can I export?
**MP4** (best for sharing), **GIF** (for autoplay loops), and **WebM**, each with quality presets. Markers become chapters in the exported MP4.

## The voiceover sounds rushed or lines overlap — what happened?
Glide times each line to fit the video and inserts brief freeze‑frames so nothing overlaps. If a script is much longer than the video, it gently speeds up the tightest lines. Shorten a line (or let Glide regenerate a tighter script) and re‑voice to fix it.

## The AI says it’s “busy / overloaded.”
That’s the upstream AI service being under heavy load. Glide automatically retries with backoff and falls back to a lighter model, so it usually recovers on its own. If it’s persistent, wait a few minutes and try again.

## Can I edit what the AI wrote?
Absolutely. Every line is editable, and you can re‑voice a single line with the **⟳** button without touching the rest.

## Where are my projects saved?
Recordings auto‑save as `.glide` projects (a folder bundle) so your edits and voices persist. Use **Save a copy…** to write a named copy somewhere else.

## Is Glide signed?
Yes — Glide is signed and notarized with a Developer ID, so it opens without Gatekeeper warnings.
