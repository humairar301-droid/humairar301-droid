<!--
  GITHUB PROFILE README
  Letakkan file ini di repository bernama SAMA dengan username GitHub kamu
  (mis. repo "humaira45" untuk user github.com/humaira45) → file README.md-nya
  otomatis tampil di halaman profil GitHub kamu.
  Ganti semua [PLACEHOLDER] dengan data kamu sebelum publish.
-->

<h1 align="center">humaira45</h1>
<p align="center"><b>Smart Contract Security Researcher</b> · 🇮🇩 Indonesia</p>
<p align="center"><i>"Diving into smart contract security and enjoying the process. Always learning, always improving."</i></p>

<p align="center">
  <a href="https://immunefi.com/profile/humaira45/"><img alt="Immunefi" src="https://img.shields.io/badge/Immunefi-Profile-6E3AFF?style=for-the-badge"></a>
  <img alt="Rank" src="https://img.shields.io/badge/All--time_rank-%23279-success?style=for-the-badge">
  <img alt="Reports" src="https://img.shields.io/badge/Confirmed_reports-14-orange?style=for-the-badge">
</p>

<p align="center">
  <img alt="Critical" src="https://img.shields.io/badge/Critical-3-red">
  <img alt="High" src="https://img.shields.io/badge/High-2-orange">
  <img alt="Medium" src="https://img.shields.io/badge/Medium-3-yellow">
  <img alt="Low" src="https://img.shields.io/badge/Low-6-lightgrey">
</p>

---

## 👋 About

Independent smart-contract security researcher focused on **DeFi economic & invariant bugs**.
Active on [Immunefi](https://immunefi.com/profile/humaira45/) since **September 2025** — **14 confirmed/paid
reports** (3 Critical · 2 High) on protocols including **Livepeer, Enzyme, Harvest Finance, Alchemix V3,
Sky (Maker), Obyte, and Floe Labs**.

My edge isn't pattern-matching — it's **invariant-first hunting**: I extract a protocol's economic
promises (solvency, value-conservation, share-price integrity), attack them with **multi-step adversarial
sequences across modules**, and **prove every finding by execution** rather than by argument.

---

## 🏆 Selected Findings

| Sev | Protocol | Impact | Status |
|:---:|:---|:---|:---:|
| 🔴 Critical | Obyte | Reward double-claim → protocol insolvency | Paid |
| 🔴 Critical | Obyte | Governance state-machine flaw → permanent freezing of funds | Paid |
| 🔴 Critical | Alchemix V3 | Liquidation accounting flaw → theft of unclaimed yield | Paid · Audit Comp |
| 🟠 High | Livepeer | Reward-claim flaw → fees made permanently unclaimable | Paid |
| 🟠 High | Alchemix V3 | TVL accounting drift → deposits blocked | Paid · Audit Comp |
| 🟡 Medium | Floe Labs | Collateral over-pull → temporary freezing of funds | Confirmed |
| 🟡 Medium | Alchemix V3 | Swap-payload decode flaw → temporary freezing of funds | Paid · Audit Comp |
| 🟡 Medium | Alchemix V3 | Unchecked external return → withdrawals revert | Paid · Audit Comp |
| ⚪ Low | Livepeer | Cross-layer migration flaw → permanent ETH freezing | Paid |
| ⚪ Low | Livepeer | Migration-claim flaw → temporary freezing of stake/fees | Paid |
| ⚪ Low | Alchemix V3 | Missing swap input validation | Paid · Audit Comp |
| ⚪ Low | Harvest | ERC4626 preview accounting overestimate | Paid |
| ⚪ Low | Sky (Maker) | Keeper job division-by-zero → DoS | Paid |
| ⚪ Low | Enzyme Blue | Adapter leftover-asset freezing | Paid |

> Severity tiers and impact categories only. Detailed write-ups and PoCs are shared privately on request, in line with each program's responsible-disclosure policy.

---

## 🎯 Bug Classes I Specialize In

- 🧊 **Fund freezing** (permanent & temporary) — stranded collateral, blocked withdrawals, refund-to-alias, missing flush
- 💸 **Protocol insolvency / unbounded issuance** — double-claim, accounting drift, fee leaks
- 🔢 **Economic & accounting bugs** — ERC4626 share/preview math, TVL drift, liquidation accounting
- 🗳️ **State-machine & governance freezes** — unbounded loops, irrecoverable states
- 🧩 **Integration & decode bugs** — ABI mismatch, unchecked return codes, missing input validation
- ⛔ **DoS** — division-by-zero, gas/loop griefing on keepers and jobs

## 🧰 Toolbox

![Foundry](https://img.shields.io/badge/Foundry-000?logo=foundry&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)
![Echidna](https://img.shields.io/badge/Echidna-fuzzing-2C3E50)
![Medusa](https://img.shields.io/badge/Medusa-fuzzing-2C3E50)
![Halmos](https://img.shields.io/badge/Halmos-symbolic-2C3E50)
![Slither](https://img.shields.io/badge/Slither-static-2C3E50)
![Anchor](https://img.shields.io/badge/Anchor-Solana-9945FF)

**Chains/VMs:** Ethereum · Arbitrum & L2s · Solana (Anchor/Token-2022) · Obyte (Oscript AA) · Stacks (Clarity)
**Methods:** invariant/stateful fuzzing · symbolic execution · mainnet-fork PoCs · differential (deployed-vs-audited) review

## 🔬 Methodology

1. **Invariant-first** — extract the protocol's economic promises before reading line-by-line.
2. **Diverge then converge** — generate every hypothesis during the hunt; kill ruthlessly at the gate (in-scope, non-privileged, end-to-end, net-positive).
3. **Execute, don't argue** — every economic finding is confirmed with a fuzzer + fork PoC. *No PoC = hypothesis, not a finding.*
4. **Steelman before submit** — I attack my own report as a hostile reviewer first. Survives → submit.

---

## 📫 Reach me

- 🛡️ Immunefi: [immunefi.com/profile/humaira45](https://immunefi.com/profile/humaira45/)

<p align="center"><sub>Open to private bug-bounty invites, audit contests, and collaborative reviews.</sub></p>
