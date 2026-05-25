This is a single, fully online (no install, and the tracker still saves each device's collection locally.) — open it in any browser (on a phone, tap the share menu → "Add to Home Screen" so a kid can use it like a real app). Everything saves automatically on the device, plus there's a backup file option.
What it does, and how the source material shaped it:

992 stickers, kid-simple input. Organized into Opening Pages, 48 team blocks of 20, and a separate Coca-Cola section. The core action: tap a sticker once each time you pull it from a pack — first tap = got it, more taps = doubles. The Coca-Cola section carries a note that those 12 come from marked bottles, not packs (Phase 4).
Trade tab. Auto-generates "my spares to offer" and "still need" lists, so no flipping through the album (Phase 2).
Swap code + QR. Generates a scannable QR and a text code of the whole collection. A friend scans it (or pastes the code) and the app instantly shows the two-way match — what they can give you and what you can give them (the Swap-26 QR idea).
Star flagging. Mark Messi/Ronaldo/Yamal-type shinies so they're highlighted and not traded away cheaply (Phase 3 market value).
Stats tab. Album %, per-section progress, and a pack/cost tracker with the "~150-pack sweet spot" guidance and the "final 50 → Panini Missing Sticker Service" tip.

Verification done: the QR encoder was built from scratch and confirmed byte-identical to a reference library and decodable by two independent decoders; the swap-code round-trip and friend-matching logic were unit-tested; and the full app was run headlessly — 50 sections / 992 stickers render and every tab works with no script errors.
Two things to know: I couldn't read the Athletic article — that domain is blocked for me to fetch — so the app is built on the Gemini write-up plus general Panini knowledge; if you paste the article text I can fold in anything I missed. Also, the 48 team blocks are named "Team 1–48" by default — tap the pencil to rename each as the draw firms up. QR scanning uses the browser's built-in detector (works on Android/Chrome; on iPhones the paste-the-code path always works).
