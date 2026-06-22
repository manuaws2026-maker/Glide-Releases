# Features in depth

Every panel in Glide, and what it does.

## Background
Frame your recording so it looks designed rather than captured.
- **Type:** system wallpaper, gradient, solid color, a blurred copy of your screen, or your own image.
- **Background blur:** soften the wallpaper or image so the recording stands out in front of it.
- **Padding:** how much space sits around the recording.
- **Corner radius & squircle:** rounded corners, with an Apple-style superellipse for a softer curve.
- **Shadow:** intensity, angle, distance, blur, and optional directional light.
- **Inset border:** a subtle inner frame in any color or opacity.

## Cursor
Make the pointer feel intentional.
- **Smoothing:** spring-based motion that eases between targets instead of snapping.
- **Size:** scale the cursor up so it's easy to follow.
- **Click effects:** a ripple or highlight on every click.
- **De-shake:** smooths tiny cursor jitter around each click so clicks look deliberate.
- **Hide when idle:** fade the cursor out when it stops moving.

## Zoom
The feature that makes demos feel alive.
- **Auto-zoom:** Glide generates zoom-ins from your clicks automatically.
- **Zoom level:** how far it punches in.
- **Zoom speed:** spring stiffness, smoothness, and momentum presets for the in/out motion.
- **Keep zoomed in:** stay punched in instead of returning to full frame.
- **Manual zooms:** add, move, and resize zoom blocks on the timeline.

## Camera
A webcam bubble done tastefully.
- **Size & position:** any size, in any corner.
- **Roundness:** from rounded-square all the way to a perfect circle.
- **Mirror:** flip horizontally.
- **Scale during zoom:** the bubble shrinks while the screen is zoomed so it never blocks the action.

## Crop & mask
- **Crop:** trim the frame to just the region you want to show.
- **Mask:** draw regions to blur or hide sensitive parts of the screen, like passwords, emails, or faces.

## Audio
- **Microphone & system audio:** independent levels and mute.
- **Voice clean-up:** reduce background noise on the mic.
- **Background music:** drop in a track that ducks automatically under narration.
- **Click sounds:** optional audible feedback on clicks.

## Captions & keystrokes
- Auto-transcribed from your narration, with fully editable text and timing and adjustable size.
- **Keystroke overlay:** show the keys you press as on-screen badges (e.g. ⌘C), with options for showing single letters and adjusting badge size.
- Useful for silent autoplay on social.

## Voiceover (AI)
- **Describe your product** in a sentence and Glide writes a natural, audience-aware script by watching the video.
- **Lifelike voices:** pick a voice and Glide speaks the script.
- **Auto-fit:** lines are timed so they never overlap or run past the video.
- **Per-line control:** edit any line and re-voice just that one.
- **Your own voice:** record narration yourself instead.
- **Voice cloning:** record a short sample (or upload one) and Glide creates a custom AI voice you can narrate in, without leaving the app. Needs a paid ElevenLabs plan.
- **Transparency:** a live activity view shows what the AI inferred and how it scored each draft.

> The AI voiceover uses your own API keys (Google Gemini for the script, ElevenLabs for the voice), stored encrypted on your Mac. See the [FAQ](faq.md).

## AI avatar presenter
Put a presenter on screen without filming yourself.
- **Pick an avatar & voice:** choose a lifelike avatar and voice, and it reads your finalized voiceover script.
- **Talking-head overlay:** the rendered avatar drops onto your recording as a picture-in-picture presenter, lip-synced to its own voice.
- **Stays in sync, never cut off:** the avatar plays on its own clock and the timeline auto-extends to fit, holding the last screen frame if the presenter runs longer than the recording.
- **Choose upfront:** pick a voiceover or an avatar, so you don't spend voice credits you don't need.
- **Your webcam stays safe:** if you recorded your own camera, it's preserved as a separate copy, and you can switch back to it anytime with one click.

> The AI avatar uses your own **HeyGen** API key, with API credits enabled (separate from a HeyGen studio plan), stored encrypted on your Mac. It's pay-as-you-go at roughly $3 to $4 per minute of avatar video, billed to your HeyGen account. See the [FAQ](faq.md).

## Motion blur
A touch of cinematic blur on fast cursor moves and zoom transitions, so motion reads as smooth rather than abrupt. Tunable per source (cursor, zoom, pan).

## Timeline
- Trim and cut clips, and change playback speed.
- Separate tracks for zooms, captions, and voice.
- Freeze frames are inserted automatically when needed to fit narration, and they stay editable.

## Export
- **MP4**, **GIF**, or **WebM**, at your chosen aspect ratio (16:9, 9:16, 1:1, 4:3), resolution, and frame rate.
- Quality presets.
- Embedded chapters from your markers.
- Export captions as an **SRT** subtitle file, or save the current frame as a **PNG**.
