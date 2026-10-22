# Prismelle support and privacy

Public static pages for Prismelle: Light Puzzles.

- Privacy: https://cgq-source.github.io/prismelle-support/privacy.html
- Support: https://cgq-source.github.io/prismelle-support/support.html
- Privacy and terms: English, Simplified Chinese, Traditional Chinese, Japanese, German, French, Spanish, Brazilian Portuguese, and Korean.
- Home and support: all nine languages above. No scripts, tracking pixels, or external fonts.
- Publish the root of `main` using GitHub Pages.

Source is maintained with the app under `PrismelleIOS/app-store-pages/`. Review the policy whenever data practices change, including before adding ads, Game Center, cloud sync, or remote diagnostics. Local purchase diagnostics are separate from the transaction identifier stored in the on-device hint ledger.

The dark indigo, glass-prism and warm-gold website theme was approved on 2026-09-18. The background is the app’s existing HomeOptics artwork, hosted locally as `assets/prismelle-background.png`; no remote fonts, scripts or image services are used. The original language anchors remain available in full.

## 2026-10-22 upcoming benefits update

All four public pages now describe the upcoming 69-level Classic campaign and current 23-shape collection, with 25/3 free levels and voluntary rewarded unlocks for up to 3 following levels. The nine-language terms and privacy policy explain the 30-hint Pro gift, per-run minimum 4 and rounded-up half-inventory allowance, ordinary/Pro achievement and ad rewards, first-clear rewards and verified legacy-Pro adjustments. Pro has no forced ads; an exhausted Pro player can actively choose an ad for 4 hints. Ordinary interstitials are limited to first clears 8/16/24, with no catch-up; shapes have none.

The pages distinguish the forthcoming app benefits and shape leaderboard approval from the currently installed release, and do not change or promise a current App Store price. They describe separate Classic/shape Game Center counts, local 48-hour return notifications after at least 6 distinct clears, app-language-aware Apple update checks, and the distinction between supported private CloudKit data and local shape boards. Apple Standard EULA, support contacts, nine language anchors, SDK disclosures, and the established website styling remain. No new license or liability clauses were introduced.

Validation: `Tools/legal-pages/validate.py`; publication and independent readback are recorded in the app repository's 2026-10-22 QA evidence. App Store submission remains a separate user action.

## 2026-10-03 version 1.0.3 legal pages (published)

Privacy and terms now cover the independent 19-level Refraction chapter (6 free, 13 Pro), all seven achievements, unchanged one-time Pro access, separate chapter progress, and the classic-only leaderboard. Both pages contain nine complete language sections. The original four anchors remain available. The Apple Standard EULA remains linked; this update adds no new license or liability terms. StoreKit, Game Center, private CloudKit, local diagnostics, support correspondence and deletion disclosures remain covered.

Published only `privacy.html`, `terms.html`, and the support repository README in `cgq-source/prismelle-support`, commit `8e3e545f60c7ff459cb618adf8ecb76f2ba15717`. GitHub Pages built this commit; public content matches local hashes. No application source, build or App Review action changed. Generation and link checks: `../Tools/legal-pages/`; publication evidence: `../docs/commerce/app-store-1.0.3-build28-20261003/website-103/`.

Build28 keeps its existing website anchor fallback for newly added application languages; readers can select the new language sections on the page. Home/support remain four-language pages. Layout verified at actual 360px and 1280px content widths with no horizontal overflow or overlapping language links. The existing design is preserved; the Chinese terms heading stays together on narrow screens.

## 2026-09-18 Game Center update (published 2026-09-19)

The four-language privacy source now describes achievement reporting to Apple, the on-device game-scoped player identifier and ownership ledger, offline synchronization, and the distinction from full cloud saves. This policy and the subsequent Journey leaderboard update were published on 2026-09-19. See `../docs/61-game-center-achievements.md`.

## 2026-09-19 formal candidate materials

Build 14 disables the default 1200-hint test grant while preserving existing balances. The local support page now explains sequential level unlocking with Pro and hides the Home Pro entry after purchase. All four privacy sections include Journey leaderboard handling. Both pages were published through the GitHub web editor and verified against the public GitHub Pages responses. Commits: privacy `836541dacc23207527bfd06c5a8881ea1bf36590`, support `b3883faf1b0fd3407a63464376107e378a19825a`. Records: `../docs/commerce/app-store-setup-20260919/website-status.json` and `website-public-verification.json`.
