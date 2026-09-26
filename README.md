# GARAGE THROUGH TIME

Windows co-op action game from MakeWay Studios. This repository is reserved for public Windows releases and update metadata.

Download **[GarageThroughTime-Setup.exe](https://github.com/makewaystudios-beep/GarageThroughTime-Releases/releases/latest/download/GarageThroughTime-Setup.exe)** or visit [Releases](https://github.com/makewaystudios-beep/GarageThroughTime-Releases/releases/latest). Current game: **0.3.7 — Return portals and shared expeditions**.

**Existing players: run the new small Setup once and select your existing game folder.** Older shortcuts will ask for the newer launcher before downloading anything. Keep your installation and saves; the new updater reuses matching files and data inside the game pack. After this one-time step, use the **Garage Through Time** Desktop or Start-menu shortcut for automatic update checks. It downloads missing or changed content and cleans up replaced game files after a verified installation. The first installation downloads the game. Unknown or modified files are preserved separately, and player saves remain outside the installation.

For a fresh install, choose your folder with **Browse…**, then click **Install and play**. A centered progress bar shows **Downloading…** or **Installing…**. When the game opens, choose **Play on desktop** or **Play in VR**.

Everyone connects to the same public garage automatically. No LAN section, Host, Join, server selection or address entry is needed. Up to six players share the server, with six separate garage spawn points. You can see the other travelers currently in the garage. Meet at the time machine and confirm the crew's ready check to depart together. New arrivals enter the garage even while a crew is away, and can join that operation without resetting it.

Your first trip begins without combat weapons. A guide calls **“Follow me!”**, waits when you fall behind and leads you through cover toward a charging zone. Nearby fighting, arrows, overlapping positional battle cries, drifting dust and blood impacts fill the battlefield. Back home, prepare a free loadout at the weapons bench before the next expedition.

The return device is always available in **slot 4** on a mission and starts empty on every deployment. Charge it in a marked zone, then shoot a broad ground or wall surface to open a portal home. Each traveler crosses individually. **Middle mouse closes both ends**: wait for your teammates, but watch your back—enemies can follow you into the garage. Closing the portal does not remove invaders who already crossed. Prepared players can defend the garage.

Gunfire now kicks the hands and desktop view, and taking damage adds a fading blood overlay. The player's energy shield has been removed; enemy shields remain. Hold **right mouse** for the rifle optic or pistol iron sights, with no hip-fire crosshair. VR keeps weapon recoil without forcing headset rotation. All seven enemy appearances have improved cloth, role equipment, open faces, grounded steps and hand-aligned weapons.

The illustrated **Armory** has Shop and Inventory tabs, category filters, item previews and Buy/Equip buttons. Fifty generated images cover starter equipment, ammo, upgrade tiers and finishes for the existing rifle, pistol and knife. Spend salvage, store deployment ammo and equip owned finishes; purchases and choices save per player. The garage retains cyan/violet neon, approach-only station titles and simple menus.

**AXIOM voice is optional and local to each player's PC.** The hosting PC's PersonaPlex runtime has been configured separately; downloading the game on another PC does not install or share that model runtime. Live conversation needs the separate runtime/model setup and suitable local hardware. No paid inference API or per-token allowance is used by this local configuration. Once ready, AXIOM listens in the garage; **M** mutes the microphone. The rest of the game works without voice. Setup instructions are included in `docs/PERSONAPLEX.md` and `ai/Setup-AXIOM.cmd`.

This is a **free noncommercial build**. Arm mesh/maps are by DJMaesen (CC BY-NC 4.0); source animation clips are by Cransh (CC BY 4.0). Full credits, modifications and license texts are included in `docs/FIRST_PERSON_ARMS.md` and `docs/ASSET_MANIFEST.md`. Other assets retain their separate licenses.

Experimental PC VR targets **Meta Quest 2 through Quest Link or Air Link**, with an active OpenXR runtime. Desktop and VR players use the same server. Physical headset, comfort and stereo testing remain unverified. This is a Windows PC game, not a standalone Quest app.

The dedicated garage remains open when players close their clients. Dropped connections retry automatically, and a background supervisor restarts exited server or relay processes. Availability depends on the hosting PC staying awake, online and logged in after a restart. Download availability does not mean that the game server is online. A hosting update restarts the current session; saved personal progress remains intact.

See the included game documentation for controls, credits, setup instructions and known limitations.