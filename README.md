# Fracturepoint — The End of Minecraft

**Don’t just reach the Far Lands. Push until Minecraft runs out.**

Fracturepoint is a public Minecraft Java 26.2 survival/PvP server built around a shared mathematical expedition. Your first Overworld jump lands in front of the Classic Far Lands at 12,550,821 blocks. From there, 351 persistent frontiers push through walls, stripes, sheets, sparsity, and toward the finite-double endpoint.

## Join

1. Download `Fracturepoint-26.2-1.3.3.mrpack` from the [latest release](https://github.com/dolphindadskies/fracturepoint-server/releases/latest).
2. In Prism Launcher, choose **Add Instance → Import**.
3. Select the downloaded `.mrpack` and launch it.
4. The official server is already saved: `31.220.62.89:25565`.

The pack includes Fabric 0.19.5, the exact Fracturepoint client, Sodium, Iris, Complementary Reimagined, dynamic lights, claims, and Waystones. Shaders are included but disabled by default for comfort and accessibility.

## What is different

- Eight-direction Overworld and Nether expeditions.
- 351 paid frontiers; new stops cost three survival-earned gold.
- One obvious paid action: `TRAVEL NEXT — 3 GOLD` after each completed stop.
- Going home, returning to your saved stop, calibrations, and unlocked revisits are free.
- Vanilla End exploration capped at 100,000 Journal blocks, preserving natural End Cities, ships, loot, and Elytras.
- Shared persistent terrain and builds with personal route progress.
- PvP, claims, village Waystones, and no pay-to-win store.
- Layered server-side anti-cheat plus Ledger evidence and rollback.

## Record integrity

The HUD’s **blocks from spawn** is exact `floor(sqrt(X² + Z²))`, computed only with `BigInteger` from canonical coordinates. Exact X and Z are displayed separately. Use `/expedition record` at a frontier to create a server-authoritative checkpoint containing your UUID, exact X/Z and distance, committed stage and branch, UTC timestamp, route-manifest hash, and SHA-256 proof digest.

Atlas boundaries are enforced server-side; crossing into a buffer or another stage cannot create a valid record. Historical screenshots taken from an uncommitted physical cell are not record evidence.

Read [SERVER-RULES.md](SERVER-RULES.md) before joining. No anti-cheat is infallible; reports and alerts are reviewed against server evidence rather than used for blind bans.

## Integrity

`Fracturepoint-26.2-1.3.3.mrpack`  
SHA-256: `5a5210261bd0ca8cce8002e3ec7cb29893ab1d9faa5da106a1864acb497ff2ff`

Only use the release file whose checksum matches this value.
