# BNI 121 — Bolun Liu

Networking 1-to-1 profile artifact for BNI chapter meetings. Not a client engagement — this is a **personal positioning document** used during BNI 1-to-1 sessions to brief other chapter members on who Ben is, what RightClick:AI does, and what kind of referrals fit.

## What's in this folder

| File | Purpose |
|---|---|
| [index.html](index.html) | The single-page HTML profile. Served at https://bni.3nm.io (Vercel auto-detects `index.html` as root). Bilingual EN/中文. |
| [README.md](README.md) | This file. |

## Profile structure (BNI 1-to-1 standard)

1. **Personal Profile 个人资料** — basics, family, hobbies, traits
2. **GAINS Worksheet** — Goals, Accomplishments, Interests, Networks, Skills *(rebuilt 2026-05-22, RightClick:AI brand)*
3. **Contact Sphere 业务人脉圈** — non-competing referral partners
4. **Journey 我的旅程** — career arc 2019 → 2024+
5. **Referrals 客户及引荐** — good vs bad referral fits

## Brand & voice

Full document follows the [RightClick:AI brand guide](../../marketing-site/brand-guide.html) — *Operator's Desk* palette (forest-green `#15803D` over warm paper `#FAFAF7`, ink `#0D120F`), single-family Satoshi typography with Noto Sans SC for Chinese fallback, owner-operated voice.

Voice draws from the global [`CLAUDE.md`](../../../../../../.claude/CLAUDE.md) identity layer — direct, polarising, process-first.

## Related

- Marketing site source: [`marketing-site/`](../../marketing-site/)
- Brand reference: [`brand/`](../../brand/)
- Methodology this profile leans on: Data Process Thinking Method (see [`wiki/concepts/`](../../wiki/concepts/) once authored)

## Changelog

- **2026-05-22 (afternoon)** — **Full document rebrand.** Swapped `:root` tokens to Operator's Desk palette (forest-green over warm paper). Body font Noto Sans SC + Montserrat → Satoshi + Noto Sans SC. All sections (masthead, quick-ref, Section I rule-cards, Section III contact sphere, Section IV journey timeline, Section V referrals) now on brand. Section IV/III inline styles auto-reskinned via token remap. GAINS v2 simplified to inherit root tokens (dropped its scoped `--rc-*` overrides).
- **2026-05-22 (morning)** — Rebuilt GAINS section in RightClick:AI brand voice + palette. Removed `BNI O2O Profile 档案` masthead tag. Folded the standalone Vision quote into the GAINS pull-quote.
