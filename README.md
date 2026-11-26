# Cinder Relay

A creature-catching wasteland RPG for Game Boy Color and ModRetro Chromatic, made with GB Studio. Hearth Well has run dry. You and your Coiljack follow the old water line through the Switchyard and Glass Marsh to win two keeper trials and get the pumps running again.

**[Download the playable ROM](https://github.com/joesterne/cinder-relay/raw/refs/heads/main/build/Cinder%20Relay.gbc)** and open it in a Game Boy Color emulator.

## Controls

| Action | Handheld | Browser preview |
| --- | --- | --- |
| Highlight a menu choice | D-pad | Arrow keys |
| Confirm or advance dialogue | A | Z |
| Open or close the wrist map from a location menu | B | X |

To save, return to **Hearth Well → Logbook → Save expedition**. Choose **Continue** at the title screen to resume.

## Your first expedition

1. **Choose a partner.** Your Coiljack is ready to go. To travel with Bramble, visit **Kennel → Active partner → Bramble → Take Bramble**.
2. **Search the Switchyard.** Collect scrap and old cores. At the workbench, one core yields four scrap. A capture loop costs two scrap and a field kit costs three.
3. **Track a creature.** Read its next attack before choosing your move. Brace reduces the incoming hit to one damage and adds three power to your next Strike. To catch a new species, weaken it to four HP or less and use a loop. Gentle nip leaves at least one HP.
4. **Follow the relay signal.** Defeat the keeper at Kiln Post to open the marsh gate. The second keeper waits at Salt Spire. Claimed posts supply field kits.

## Hearth Well arcade

Choose **Arcade** at Hearth Well for two free, repeatable minigames. In **Salvage Crane**, press A as the hook passes over the marked crate. Land at least two of three lifts to earn two scrap. In **Relay Echo**, watch the pointer above the bolt, drop, and gear pads, then select the three signals in order to earn a capture loop. B exits during a crane sweep or an echo answer menu.

## Deep tracks and apex dens

At Hearth Well, Coiljack starts on your team and Bramble waits in the kennel. On the trail, choose **Track creature** to look for these species.

| Tracks | Switchyard | Glass Marsh |
| --- | --- | --- |
| Mixed tracks | Coiljack, Glasswing | Glasswing, Slaghorn |
| Distinctive signs | Rustclaw (claw grooves), Ashcrow (feather trail) | Voltfin (glowing ripples) |
| Deep tracks | Rivetbat, Spoolasp, Cokemole | Reedhart, Siltnewt, Bogbell |
| Deep tracks → Apex den | Furnace Ox, after claiming Kiln Post | Mire Crown and Stormray, after claiming Salt Spire |

Apex creatures hit harder and take longer to weaken. Capture them at four HP or less. Select deep-track and apex partners under **Kennel → Active partner → More…**.

## Secrets and soundtrack

Three optional discoveries are hidden around the valley. Check **Hearth Well → Logbook → Relay status** to see how many you have found. Each pays out once.

Three original chiptunes accompany the expedition. *Dust on the Wire* plays in settlements and on the trail, *Copper Teeth* scores ordinary battles and keeper trials, and *Under the Crown* plays in apex battles. The [editable tracker songs](assets/music/) are included with the project.

## Training and player levels

Each partner has its own attack and maximum health. Victories improve the active partner’s attack. At the kennel, two scrap buys an attack drill or an endurance run.

Your player earns 4 XP for an ordinary wild victory, 5 for a new ordinary capture, and 8 for a keeper victory, apex victory, or first apex capture. Level 2 takes 8 XP. Each subsequent level takes 4 more XP than the previous one, up to level 10. Each level increases field-kit healing by one HP. Check **Hearth Well → Logbook → Player level** for your current progress.

## Edit and build

Clone or download this repository, then open [project.gbsproj](project.gbsproj) in GB Studio. The game was built with GB Studio 4.3.2. Use the editor’s **Run** control to play your changes or export a Game Boy Color ROM.

The [project directory](project/) contains scenes, scripts, palettes, and variables. [Assets](assets/) contains the artwork and fonts. The compiled cartridge is in [build](build/).
