# 25Chinese

Windows desktop app for HSK study.

## Latest release — 4.3.3

Download: https://github.com/j1s4nn/25chinese/releases/latest/download/25Chinese-Setup-4.3.3.exe

SHA-256: `7d6c98b1b923b1789fb0cf1c6064f2f28fb67d024d999781afc0f1aaa233119c`
Size: 98,482,397 bytes (93.92 MB)

### What changed in 4.3.3

- The weekly AI paper is now a real exam maker. Choose 0-20 fill-in-the-blank, 0-10 short reply, and optionally one 4-20 turn AI dialogue or an 80+ character writing task.
- Dialogue and writing model answers stay sealed after submit. Revealing them costs 5 requests once; a retry is free.
- Fixed the AI explainer returning a fragment instead of JSON, so explanations now load as real AI output.
- Explain keeps punctuation in the pinyin line, colours every unit and bolds grammar, verbs, adjectives and adverbs.
- Meaning table merges mono-, di-, tri- and tetra-character units plus set phrases and proverbs (你今天是不是有点紧张呀 → 你 / 今天 / 是不是 / 有点 / 紧张 / 呀).
- No literal `**` and no "meaning unavailable" placeholders anywhere in explanations.
- The assistant is now a professional Markdown editor: compact section labels, a bordered structure box, and numbered examples as three stacked Chinese / pinyin / English lines in matching colour.
- The per-row Note button verifies the unit with one request and saves it to the permanent, deduplicated "new collection characters" notebook note.

Older installers stay on the Releases page for rollback. Every release ships the installer and a checksum file so you can verify the download before installing. The app updates itself from the signed update feed.

Source code is not published in this repository.
