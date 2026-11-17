# Scout Live Demo - Eyes and Voice

A standalone public site for Scout, the small wheeled interactive robot Kenneth is building. This is the same demo that lives in Muse as the Scout Live Demo artifact, now hosted outside Muse so anyone with the link can open it, no Muse needed.

What it does:
- Animated Scout face: 8 expressions, blinking, gaze, talking mouth, live status.
- Chat brain in the page: answers once per question, jokes, singing, who built Scout, robot parts guessing game.
- Memory panel in the session: tell it a fact, ask what it remembers, it recalls it. Memory in this demo is session only. The real long-term memory is scout_memory.py in the scout-robot Python brain.
- Voice Lab: Fenrir, Orus, Charon, Algenib to test and lock in. Note: this web demo plays character tunings of the device's installed speech voice, not real Gemini recordings. For the real Gemini voices in Nigerian English (en-NG), use voice_test.py in the scout-robot folder.
- English only, hard rule: Scout speaks English only, always, with a warm male Nigerian accent. Type Spanish or Hindi and Scout replies in English only and asks for a repeat in English. A language guard warns and asks Scout to repeat any non-English reply in English.

Deploy: static site, just index.html. Hosted on Vercel.
