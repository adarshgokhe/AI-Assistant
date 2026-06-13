Nova AI Mic Toggle + Speech Network Fix

This version keeps old functions intact and fixes the voice ON/OFF behavior.

Fixed:
- Start Voice button is now a real toggle. Click once = mic ON. Click again = mic OFF.
- Desktop Mic button uses the same toggle.
- Browser speech network hiccup messages no longer keep the mic stuck.
- Main voice mode now uses desktop microphone loop first, because browser speech can show network/service hiccup even when internet works.
- Old WhatsApp, Spotify, app opening, memory, contacts, security, settings, laptop scan features are kept.

Run:
python nova_ai_ultimate.py --web

If microphone package has problems, run INSTALL_AUDIO_FIX.cmd once, then restart Nova AI.
