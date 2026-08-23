# Wife Index (WI) — Development & Changelog

## Project Summary
A real-time satirical yet quantitatively sound dashboard tracking Bitcoin network and market telemetry translated into domestic marital sentiment, garage acoustics, and household purchasing power.

* **Repository:** `backwater-mining-collective/bitcoin-wife-index` (GitHub Pages)
* **Custom Domain:** `wifeindex.com` (CNAME provisioned)

---

## Change History & Milestones

### 2026-08-22: Name Update to "Wife Index" (WI)
* Streamlined the masthead and branding to **WIFE INDEX** across `index.html`, `index.cabin.html`, and `README.md`.
* Updated the header logo badge from `BWI` to `WI`.
* Re-rendered favicon assets (`favicon.svg`, `favicon.png`, `favicon.ico`) with the **WI** monogram.

### 2026-08-22: Full Dashboard Build, Custom Domain, & Deployment
1. **Interactive Metric Inputs & Live Resets**
   * Added numeric override inputs and `LIVE` reset buttons across all dashboard blocks:
     * *Unsolicited Monologue Probability* (`%` input, real-time risk recalculation).
     * *Whole Foods & Sur La Table Cart Clearance* (ATH drawdown `%` input with automatic negative clamping).
     * *Coffee Line Public Embarrassment* (`sat/vB` input with logarithmic mempool friction curve).
     * *Garage Decibel & Heat Permit* (Score `0–100` override).
     * *Subpanel / Breaker Roulette* (Amperage `A` load override vs. 50A NEC 80% continuous limit).
     * *Hashrate Heating & Utility Bill Offset* (Monthly bill `$/mo` override against $185/mo baseline).
     * *Infinite Household Supply vs. 21M Cap* (Item `#` selector `0–49` across 50-item domestic stockpile dataset).
     * *Boomer In-Law Capitulation Meter* (Spot price `$` simulator with tiered milestone commentary).
     * *Halving Epoch & Difficulty Retarget* (Estimated difficulty adjustment `%` override).
     * *Tangible Goods & Real Estate Parity* (Custom spot price `$` live parity calculator).
     * *Husband Model Target (Whiteboard Delusions)* (Step input in $25k increments with delusion meter).

2. **Code & Formula Audit**
   * Verified on-chain hashprice math (`465 BTC/day ÷ network TH × spot`).
   * Unified lottery and big rig hashrates in combined daily revenue and monthly mined USD.
   * Enforced bounds clamping on item indices and power rates.
   * Fixed DOM element targets (`epoch-source` header subtitle binding, `status-good` class styling).

3. **Theme & UI Polish**
   * Live Theme: *Heavy Industrial Garage Workshop* (hazard accents, gunmetal steel, Teko/Chakra Petch typography).
   * Backup Theme: *Modern Rustic Cabin & Timber* (`index.cabin.html`).
   * Cleaned up Parity card (removed static historical drawdown line).
   * Footer updated with a styled GitHub logo button linking to the repository.

4. **Repository & Hosting Setup**
   * Initialized git repository with verified commit author.
   * Created public GitHub repository: `backwater-mining-collective/bitcoin-wife-index`.
   * Added `CNAME` configured for `wifeindex.com` and activated GitHub Pages.
   * Sanitization audit passed: 100% clean of private local paths, IPs, or credentials.
