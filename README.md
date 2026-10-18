# JARVIS for Mac

A voice assistant for macOS powered by Claude Code: wake word, speech, an on-screen display and a phone page.

- Site: https://tlkb2109.github.io/jarvis-download/
- Download: https://github.com/TLKB2109/jarvis-download/releases/latest/download/JARVIS-Mac.zip

Unzip, then run `bash JARVIS/setup.sh`. Full instructions are in the README inside the zip.

## First launch

On a brand-new install Jarvis speaks a one-minute welcome (wake word, typing, what he can do, the background assistant Edwin, the on-screen display, optional connectors) and offers a tour. Say "Hey Jarvis, give me the tour" any time to hear it again, one piece at a time.

- Voice or typing: say "Hey Jarvis" and talk, or type in the Jarvis window (`/mute`, `/unmute`, `/reset`, `/status`, `/help`, `/exit`).
- Try: "Good morning", "Set a timer for 20 minutes", "Remind me to call the dentist at 4", "What's on my calendar tomorrow?", "Email Sam that I'll be late" (he asks before sending), "Play some Miles Davis".
- Connectors (optional): claude.ai > Settings > Connectors, connect Gmail, Google Drive, Google Calendar and Spotify once. Skip any you don't want.
- Background jobs: for long tasks he says "passing it to my assistant" and Edwin keeps working across restarts, announcing the result.
- Timers and reminders survive restarts; reminders land in the Mac's Reminders app.
- The display and its characters (Mavis, plus ABG, Mario, Felix and Li Laoshi on request) can be turned off with `JARVIS_HUD=0`.
- Memory starts empty: say "remember that..." and it sticks (daily log, running jokes, topic files plus an index; all on your Mac). Ask "what do you remember about me?" to see it, say "forget that" to delete it.
- Skip or replay the welcome: `JARVIS_INTRO=0` in `.env`, or delete `.intro_done`.

The full written tour is `GETTING_STARTED.md` inside the zip.
