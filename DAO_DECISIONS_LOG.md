# ONTON DAO — Official Decisions & OIP Historical Track Record

This ledger records all **ONTON Improvement Proposals (`OIP-1` through `OIP-7`)**, their Review Council & Senate vote tallies, Telegram and GitHub evidence links, and current engineering delivery status.

---

## 1. Summary Table (`OIP-1` – `OIP-7`)

| OIP | Title | Proposer / Authors | Vote & Evidence Record | Status |
| :--- | :--- | :--- | :--- | :--- |
| **`OIP-1`** | **25% DAO Net Revenue Covenant & 3-Chamber Constitution (`60/40` Baseline)** | Core Team (`2026-10-18`) | Ratified at ONTON 2.1 launch (`onton.live/dao`). Locks `625.51M $ONIT` across 6 Macro Plans until `$20M FDV`, sets the `5%` per-wallet voting cap, and allocates `25%` of net platform fee revenue to the DAO (`60%` STON.fi LP / `40%` JVault Staking baseline). | **✅ Shipped & Active** *(Layer 1/2 split amended by `OIP-6` once net revenue reaches `$3,000/qtr`)* |
| **`OIP-2` & `OIP-3`** | **Early Working Drafts: Dynamic Revenue Split & Self-Funded Organizer Fee Rebates / Co-Host Grants** | `@adekvatushka` & Review Council (`2026-10-19` – `2026-10-21`) | Senate Topic `#745` (`#288`, `#528`). Organizer Fee Rebates (`2.5%` Pro Tier) and Co-Host Event Grants shipped directly; dynamic revenue split draft was consolidated and numbered as **`OIP-4`**. | **🔄 Consolidated into `OIP-4` & Shipped** |
| **`OIP-4`** | **Dynamic Buyback, DEX Liquidity & Staking Yield Split (`80/20`, `60/40`, `40/60`)** | `@adekvatushka` (`2026-10-22` – `2026-10-26`) | Concluded `2026-10-26` (`93.6%` approval, Senate `#793`). Later expanded by `@adekvatushka` and the Review Council into **`OIP-6`** to add the Genesis NFT Layer 1 pool and `$3,000/qtr` revenue floor. | **✅ Concluded & Refined by `OIP-6`** |
| **`OIP-5`** | **SBT Alchemist Workshop & Luck Essence Marketplace** | `@adekvatushka`, `@UglyDemoN`, `@OneMillionExabytesPerSecond` (`2026-10-23` – `2026-10-26`) | Stage-1 72h working draft poll concluded `2026-10-26` (Senate `#614`, `#657`, `#676`). Interactive UI demo is live at `/my/badges?tab=alchemist`; Phase 2 on-chain crafting is gated behind the `$3,000/quarter` revenue floor. | **⏸️ Demo Live / Phase 2 Gated (`$3k/qtr`)** |
| **`OIP-6`** | **Two-Layer DAO Revenue Pool, Equal Genesis NFT Rights, 2-Level Per-NFT Yield & 15% `$ONIT` Ticket Discount** | Review Council (`@MERUSAKA`, `@adekvatushka`, `@OneMillionExabytesPerSecond`, `@mrDenai`, `@UglyDemoN`, `@demiurgosz`) | [`onton-community#10`](https://github.com/ontonlive/onton-community/issues/10) · Senate Topic `#745` (`#817`–`#819`, official resolution `#883` on `2026-11-03`). **Vote A Winner:** **Option A2 (`7,000 $ONIT` Platinum / `3,250` Gold / `1,500` Silver / `1,000` Bronze)** (`11` vs `8` raw / `11` vs `3` deduplicated). **Vote B Winner:** **`50%` Layer 1 (Genesis NFT Base) / `50%` Layer 2 (`$ONIT` Staking)** (`14` vs `8` raw / `9` vs `8` deduplicated). | **✅ Passed (`2026-11-03`) — In Delivery** |
| **`OIP-7`** | **Proof of Unique Human & Activity Shield (Anti-Multi-Account System)** | `@adekvatushka` & Review Council (`2026-10-28`) | [`onton-community#9`](https://github.com/ontonlive/onton-community/issues/9) · Senate Topic `#745` (`#821`, Review Council `#394`, `#403`, `#436`). **Rule 1 (Active Now):** Multi-wallet clusters funded from or sweeping to a single hub wallet count as **1 single voter** in Senate polls. **Rule 2:** Activity & wallet filter for prize raffles and referrals. | **🟢 Rule 1 Active in Senate Votes / Rule 2 Queued** |

---

## 2. Detailed Record of Passed Decisions

### `OIP-6` — Ratified Parameters (`2026-11-03`)
- **Source & Evidence:**
  - Public Proposal Issue: [`ontonlive/onton-community#10`](https://github.com/ontonlive/onton-community/issues/10)
  - Senate Topic `#745` Thread & Polls: `https://t.me/c/4337087590/745/817` (`#818` Vote A, `#819` Vote B, `#883` Final Results)
  - Review Council Sign-Off & Cluster Audit: `#279`–`#282`, `#394`, `#436`
- **Ratified Rules:**
  1. **Equal NFT Rights (Zero Origin Penalty):** Every Genesis ONION NFT of the same tier has identical rights whether minted originally on ONTON or bought on Getgems (`+1.0x` Platinum, `+0.5x` Gold, `+0.25x` Silver, `+0.1x` Bronze).
  2. **No Per-Wallet Payout Cap:** Every activated Genesis NFT earns its full tier share (the `5%` per-wallet cap applies strictly to DAO voting power).
  3. **2-Level Per-NFT Yield Unlock (Vote A Winner — Option A2):**
     - **Starter Yield (`10%` of tier weight):** Active automatically for every Genesis NFT even with `0 $ONIT`.
     - **Full Yield (`100%` of tier weight):** Unlocked per individual NFT when backed by **`7,000 $ONIT` per Platinum**, **`3,250 $ONIT` per Gold**, **`1,500 $ONIT` per Silver**, and **`1,000 $ONIT` per Bronze** (counting liquid wallet + staked + unclaimed FairLock `$ONIT`).
  4. **Two-Layer DAO Revenue Split (Vote B Winner — `50% / 50%`):**
     - Once quarterly net platform revenue crosses the **`$3,000/quarter`** floor on [`onton.live/dao`](https://onton.live/dao), the 25% DAO Revenue Pool splits **`50%` to Layer 1 (Genesis NFT Base Pool)** and **`50%` to Layer 2 (`$ONIT` Buyback, Liquidity & Staking)**.
  5. **Two-Sided `$ONIT` Ticket Economy:**
     - **Attendees:** `15%` discount when paying for event/contest tickets in `$ONIT`.
     - **Organizers:** Reduced platform fee when pricing tickets in `$ONIT`.

---

## 3. Post-Decision Governance Process

When an `OIP` is ratified by the Senate:
1. **Public Ledger Update:** The final tally, winning option, and evidence links are recorded in this file (`DAO_DECISIONS_LOG.md`) and on [`onton.live/dao`](https://onton.live/dao).
2. **Engineering Triage & Priority Split:**
   - **Immediate Delivery (`priority:high`):** Features that improve live user/organizer UX or drive immediate ticket and token utility (e.g., `/my/vault` OIP-6 progress bar, `15%` `$ONIT` ticket discount, organizer referral fee share) are scheduled immediately.
   - **Revenue-Gated Delivery (`priority:low` / `status:parked`):** Automated treasury payout distributions and heavy Phase-2 mechanics (e.g., `OIP-5` Phase 2 crafting contracts, `OIP-6` Layer 1/2 automated payout worker) remain gated until the `$3,000/quarter` net revenue floor is reached.
