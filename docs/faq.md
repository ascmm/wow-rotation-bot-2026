# AEMIS — Frequently Asked Questions

## General

**What is AEMIS?**  
AEMIS is a single-button rotation engine for World of Warcraft. It evaluates SimulationCraft Action Priority Lists against your live combat state and selects the optimal next ability — within 1–13% of SimC theoretical maximum DPS.

**What WoW version does AEMIS support?**  
AEMIS supports WoW Midnight (12.x). All 13 classes and all 80 hero specializations are fully updated for the current patch.

**How is AEMIS different from other WoW rotation bots like Lumen, Phoenix, or NNR?**  
AEMIS is the only rotation engine that parses and executes real SimulationCraft APLs against live game state. Most competitors use hard-coded priority lists that drift 15–40% from theoretical maximum. AEMIS benchmarks at 1–13%.

| Tool | SimC APL accuracy | Classes | Hero Specs |
|---|---|---|---|
| AEMIS | 1–13% from max | 13 | All 80 |
---

## Detection & Safety

**Is AEMIS detectable?**  
AEMIS runs as a fully isolated service. No DLL injection, no game hooks, no native standalone addons to be detected — it uses official addons listed on CurseForge. WoW stays untouched.

**Does AEMIS modify game files?**  
No. AEMIS does not modify any game files, memory, or processes.

**Will AEMIS get me banned?**  
AEMIS is engineered to perform like a strong human player — not a synthetic top-1% parse. A safe high-80s log keeps you flying under the radar.

---

## License & Access

**How do I get access?**  
1. Go to [aemis.io](https://aemis.io)
2. Login with Discord
3. Purchase a plan via Stripe
4. Your license key is automatically bound to your Discord account

**How is the license delivered?**  
License keys are issued and bound to your Discord account automatically the moment payment clears via Stripe. No copy-paste, no support tickets.

**Can I use AEMIS on multiple characters?**  
Yes. Your license is account-bound via Discord, not character-bound.

**How many slots are available?**  
AEMIS is capped at 50 active slots. When capacity is reached, a waiting list activates. Once a member leaves, their slot does not reopen for them.

**What plans are available?**  
| Plan | Price |
|---|---|
| 1 Month | €50 |

---

## Technical

**What classes are supported?**  
All 13: Death Knight, Demon Hunter, Druid, Evoker, Hunter, Mage, Monk, Paladin, Priest, Rogue, Shaman, Warlock, Warrior. See [full class & spec list](classes.md).

**Does AEMIS support AoE rotations?**  
Yes. AEMIS detects active enemy count dynamically and switches between single-target and AoE rotations automatically.

**Does AEMIS handle cooldowns and trinkets?**  
Yes. Burst windows are automatically aligned with cooldown stacking. Both trinkets fire in the spec's burst window.

---

**→ [Get Access at aemis.io](https://aemis.io) · [Join Discord](https://discord.gg/aemis)**
