# Join Fracturepoint with proximity voice

**[Download the ready-to-play Fracturepoint pack](https://github.com/dolphindadskies/fracturepoint-server/raw/refs/heads/main/downloads/Fracturepoint-full-fallback-26.2-1.0.1.mrpack)**

This includes the voice and performance mods in the launcher's installation, so you do not have to find individual mod files.

1. Open the `.mrpack` in **[Prism Launcher](https://prismlauncher.org/download/)** or the **[Modrinth App](https://modrinth.com/app)**. Sign in with your own Minecraft account and launch the new **Fracturepoint** profile.
2. Choose **Multiplayer → Fracturepoint SMP → Join**. Accept a managed-pack download if prompted; close and relaunch this profile if it asks you to restart.
3. **First visit only: press V.** Follow the voice setup to select your microphone and headphones/speakers. Choose **Push to talk** and assign a key, or choose **Voice activation** and adjust its threshold. Use the microphone test to check your input, then finish the setup.

**Next time: launch the same Fracturepoint profile and join.** Your audio choices are saved and voice reconnects automatically. AutoModpack checks for pack updates on launch; an update may require a restart. You do not need to reinstall or repeat setup each visit.

**Server address:** `fracturepoint.duckdns.org`  
**Minecraft:** Java Edition 26.2 / Fabric 0.19.5  
**Community and help:** https://discord.gg/Wy9r5aJ4EH

## Know when voice is ready

- **Press V** to open the voice menu; **Settings** contains the microphone test and audio-device choices. Custom clients may use a different key: check **Options → Controls → Key Binds → Voice Chat**.
- **Push to talk:** hold the key you chose while speaking. It has no assigned key until you choose one. **Voice activation:** check the microphone is unmuted; **M** toggles microphone mute with the default key bindings.
- A talking icon indicates speech activity. **No icon while everyone is quiet does not, by itself, mean voice is disconnected.** A muted microphone, disabled speaker and disconnected plug are different states.
- Voice icons are enabled by default. If you hid them, open **V** and check the eye/icon visibility control and the HUD icon settings.
- Proximity voice reaches nearby players, up to approximately **48 blocks** on Fracturepoint. Two people thousands of blocks apart will not hear one another through proximity chat.

## If you cannot hear or be heard

1. Make sure you launched the **Fracturepoint pack profile**, rather than an unmodded or temporary test profile. Joining through normal Java Minecraft does not install voice mods by itself.
2. Open **V → Settings**. Select the microphone and output device you actually use, check the microphone test, and check the voice volume and talk mode. A local microphone test checks your input; it does not by itself prove another player can hear you.
3. Check that voice is not disabled, your microphone is not muted in voice-activation mode, and both players are close enough. In push-to-talk mode, hold your assigned key.
4. If you see **Voice chat not connected** or a disconnected-plug icon, disconnect from Minecraft and join again. After a pack update, fully close and relaunch this profile first. Do not reinstall everything as your first step.
5. If the disconnected state remains, ask in Discord for help. Mention the launcher/profile you used, the exact message and whether the microphone test works. A network, VPN or firewall can block voice even while Minecraft itself connects; voice uses UDP 24454. Do not disable your firewall as a general fix.

Each player chooses their own microphone and talk mode once. The pack does not turn on an always-open microphone or bypass operating-system permissions. See [Simple Voice Chat's setup guide](https://dev.modrepo.de/minecraft/voicechat/wiki/client_setup) and [troubleshooting guide](https://dev.modrepo.de/minecraft/voicechat/wiki/troubleshooting).

## Already installed? Keep your working profile

Existing players do **not** need to switch packs or reinstall. The ready-to-play download above uses the same verified mod versions as the lightweight starter; it changes when the launcher downloads them, not the gameplay.

If you prefer the smaller initial download, the [lightweight starter pack](https://github.com/dolphindadskies/fracturepoint-server/raw/refs/heads/main/downloads/Fracturepoint-starter-26.2-1.0.1.mrpack) installs AutoModpack first. Join, accept **Download modpack**, close and relaunch when prompted, then join again and press **V** for your first voice setup. Import **one** pack into a new profile; do not combine both in the same instance.

## Your saved server entry

Both imported packs include **Fracturepoint SMP** with its address and icon. Pack updates do not replace favorites in other profiles. Normal Direct Connect cannot add a favorite automatically; use **Add Server** if you join without the pack.

## What's included

AutoModpack 4.0.7, Simple Voice Chat 2.6.22, Fabric API 0.160.0, Sodium 0.9.2 and Lithium 0.25.3 for Minecraft 26.2. Voice and performance mods are optional for playing; the voice mod is required for in-game proximity voice.

Both packs include only the server's **public certificate fingerprint**, not passwords or private keys. Downloads use official publisher hosting. There are no admin tools, cheats, personal maps, shaders or personal audio-device settings in these packs. See `SHA256SUMS.txt` in this folder for artifact checksums.

## Credits

- [AutoModpack](https://modrinth.com/mod/automodpack) by Skidam and contributors.
- [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat) by Max Henkel and contributors; [modpack permission](https://dev.modrepo.de/minecraft/voicechat/faq).
- [Fabric API](https://modrinth.com/mod/fabric-api) by FabricMC.
- [Sodium](https://modrinth.com/mod/sodium) and [Lithium](https://modrinth.com/mod/lithium) by CaffeineMC and contributors.

