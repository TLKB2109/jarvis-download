# Text for the Google Site (paste into the page)

## Headline
**JARVIS — your own Iron Man assistant, on your own Mac.**
An always-listening voice assistant powered by Claude. Say "Hey Jarvis" and he answers, remembers, and gets things done: email, calendar, reminders, timers, Spotify, the web, your planner, even a second personality (Mavis) who shows up to tease.

## Download
Download for Mac: JARVIS-Mac.zip (about 200 KB; the setup downloads about 1.5 GB of speech models the first time).
Updated October 16, 2026.

## What you need
- A Mac (Apple silicon recommended), macOS 13 or newer.
- A Claude account that includes Claude Code (Pro or Max). Jarvis's brain is Claude Code running on your Mac.
- About 10 minutes.

## Setup
1. Unzip the download somewhere permanent, for example your home folder.
2. Open Terminal, type `bash ` (with a space), drag `setup.sh` into the window, press Return.
   It asks your name and a few details, installs what it needs, and pops the macOS permission prompts (microphone, Calendar, Reminders). Click Allow on each.
3. If Claude Code opens, log in with your claude.ai account, then type `/exit`.
4. On claude.ai, go to Settings › Connectors and connect Gmail, Google Drive, Google Calendar and Spotify. One time; Jarvis has full access to them from then on.
5. Double-click `Jarvis.command`, wait for "Jarvis online", and say "Hey Jarvis." He introduces himself the first time and tells you what he can do.

## Everyday use
- "Hey Jarvis" → tink → say it. Keep talking after he answers; no wake word needed for follow-ups.
- Say "Hey Jarvis" while he's talking to cut him off.
- "Never mind" ends the conversation. "Start over" begins a fresh one. "Jarvis, shut down" quits.
- You can also type in his window instead of talking.
- Emails, texts and anything else that can't be undone need your spoken "yes" first. He reads it back and asks.

## On your phone
Open the phone page from any device on your Wi‑Fi (Jarvis shows the address when he starts), or install Tailscale on the Mac and the phone to use it from anywhere. Same Jarvis, same memory.

## Privacy
Listening for "Hey Jarvis" and turning your voice into text happen on your Mac. Only the text of what you say goes to Claude. Your settings and keys live in a file on your Mac and nowhere else.

## Credits
Built by Tanner Benjamin with Claude. Wake word by openWakeWord, speech recognition by Whisper, voice by Kokoro (optional ElevenLabs).
