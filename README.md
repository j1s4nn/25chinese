# 25Chinese

Windows desktop app for HSK study.

## Latest release — 4.3.4

Download: https://github.com/j1s4nn/25chinese/releases/latest/download/25Chinese-Setup-4.3.4.exe

SHA-256: `aa1727f0ddccb48cac32c3a5d8cf3c396cc30d8bad757ac46a7be562be10507e`
Size: 98,482,392 bytes (93.92 MB)

### What changed in 4.3.4

- New-user exam-day fix: a fresh account gets a short HSK 1 starter paper instead of being told to learn cards while cards are paused.
- Free-tier AI explanation fix: the free chain now uses Qwen 3.7 Flash with a 2,500-token cap, so free users get the full AI explanation instead of a truncated offline glossary. GLM remains paid-only.
- Free Smart Video stays at 10 minutes per day (premium 2 hours).
- Carries the 4.3.3 weekly exam maker, sealed 5-request model-answer reveal, punctuation-aware pinyin, unit meaning table, grammar patterns, 1-request Note save and professional Markdown assistant.
- Clean-install and 200-user/1,000-request load audit: 0 failed requests, health p95 3 ms, accepted AI p95 943 ms, peak RSS 160 MB; 800 graceful busy responses at an instantaneous 200-user burst.

Free accounts get the free daily mission, 10 AI requests per week and 10 minutes of Smart Video per day. Extra study, extra grammar, extra correction exams and longer video tiers are Premium.

The installer is not code-signed yet, so Windows may show an "Unknown publisher" SmartScreen prompt once. The app updates itself from the signed update feed.

Older installers stay on the Releases page for rollback. Every release ships a checksum file so you can verify the download before installing.

Source code is not published in this repository.
