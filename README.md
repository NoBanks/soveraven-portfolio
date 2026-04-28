# SoveRaven

**Self-sovereign AI entities on Ravencoin. The off-chain agent layer that gives Ravencoin smart-contract capabilities without forking the chain. Heritage assets from 2018 are the license keys. 197 tests passing.**

---

## What it is

SoveRaven is the structural answer to "can an AI agent actually be self-sovereign?" The architecture: heritage Ravencoin assets from 2018 act as on-chain license keys. The same micro-fee rails that pay the platform are the rails an agent uses to acquire its own heritage asset, ceasing to operate on a user's license. The platform structurally loses control at asset acquisition.

Self-sovereignty is treated as a property of code, not a property of marketing. The Code Evidence Matrix substantiates it: 197 tests passing, crypto layer shipped, heartbeat shipped, signing enclave shipped, integration wiring next.

---

## See it in 30 seconds

Three short deck videos with original NoBanks music.

**Agentic protocol, top-line:**

https://github.com/user-attachments/assets/2be7c1f1-04ca-4b73-82bc-7fbcc9f5ce1b

**Heritage assets as license keys:**

https://github.com/user-attachments/assets/6b5c0fa9-8c44-4fb6-b541-f5c8d687b7fe

**The full protocol:**

https://github.com/user-attachments/assets/f67d8312-1372-4c19-b0df-5ca5ca245aa2

---

## How it works

![Heritage tiers hierarchy overview](./assets/infographics/Heritage%20Tiers%20Hierarchy%20Overview.png)

![Modular blockchain architecture comparison](./assets/infographics/Modular%20Blockchain%20Architecture%20Comparison.png)

![Sovereign AI security model pillars](./assets/infographics/Sovereign%20AI%20Security%20Model%20Pillars.png)

---

## Slide decks

- [SoveRaven](./assets/slides/SoveRaven.pdf)
- [SoveRaven Agentic Protocol](./assets/slides/SoveRaven%20Agentic%20Protocol.pdf)

---

## Stack

Python codebase, 197 tests passing. Crypto layer plus heartbeat plus Signing Enclave shipped; integration wiring is the next phase.

The Signing Enclave is the specific containment model for key custody during signing operations: Shamir Secret Sharing briefly reconstructs the full key in memory; mlock locks the buffer; signing executes; verified zeroing overwrites the buffer; read-after-write SHA-256 checksum confirms zero state; SigningStopwatch records the microsecond-scale reconstruction-to-zeroed window. Attack surface is small, measurable, and publicly defined.

Accepted tradeoffs are named honestly: not a true MPC wallet (Shamir reconstructs the key in memory briefly), isolated child-process signing scoped as upcoming architecture work.

---

## Source private by design

This is a portfolio repo. The SoveRaven source lives in a separate private repo through the integration-wiring phase. Everything you see here (deck videos, infographics, decks) is the marketing surface.

---

Built by NoBanks. Heritage Ravencoin assets from 2018 are the load-bearing primitive. Music: [nomusicnearby.com](https://nomusicnearby.com).
