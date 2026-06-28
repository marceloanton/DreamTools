[h1]DreamTools - Private Coop Utility[/h1]

[b]DreamTools[/b] is a trainer/utility mod for [i]Shape of Dreams[/i] focused on single-player and private co-op sessions with friends.

[h2]Updates / Manual Download[/h2]
Steam Workshop updates are temporarily rate-limited. Until Steam allows the Workshop item to update again, download the latest DreamTools package here:

[url=https://github.com/marceloanton/DreamTools]https://github.com/marceloanton/DreamTools[/url]

Extract the ZIP and copy the `DreamTools` folder into the game's `Mods` folder.

[h2]Migration Notice[/h2]
DreamTools is the continuation of the old BirkaMod project under a cleaner public name.

[list]
[*]The old BirkaMod project will be retired/deleted.
[*]Future updates will continue under DreamTools.
[*]If both DreamTools and BirkaMod appear installed, keep DreamTools and remove the old BirkaMod entry to avoid loading two copies.
[*]The dt_* command metadata is documented in-game; startup console registration is skipped to avoid loader scan errors.
[/list]

[h2]What It Does[/h2]
[list]
[*]Adds an in-game trainer menu with [b]F5[/b].
[*]Uses a game-style panel with pages for Status, Combat, Auto Attack, Resources, Player Utility, HUD / UI, Map / UI, Host / Server, Network / Coop, Commands, Diagnostics and Hotkeys.
[*]Shows local status: HP, mana, level, XP, gold, dream dust, stardust/platinum tools.
[*]Adds configurable multipliers for damage, XP, gold, dream dust, stardust, movement speed, attack speed and ability haste.
[*]Adds combat utility: god mode, infinite mana, no cooldowns, auto-heal and shield controls.
[*]Adds Auto Attack / Auto Cast with basic, primary, secondary, Q, W, E and R controls plus rotation modes.
[*]Adds resource buttons: gold, dream dust, stardust amount/multiplier and platinum.
[*]Adds loot magnet with explicit stardust pickup support, free shop and free upgrade toggles.
[*]Adds map tools: reveal map, select random/generated nodes by index/type and travel to selected node.
[*]Adds unlock tools for all heroes and hero skills in the local profile.
[*]Adds EN/ES/PT menu language selector that applies immediately.
[*]Adds optional Render Light Safety for the known URP light-cookie bounds error; disabled by default.
[*]Separates options by [b]Client Side / Local[/b], [b]Host / Server[/b] and [b]Network / Coop[/b] with colored in-game headers.
[*]Adds private co-op request mode: friends can request actions, but the host approves/executes them.
[*]Shows Visible loading progress after Apply Mod and localized diagnostics while DreamTools finishes initializing.
[/list]

[h2]Upload Changelog[/h2]
[list]
[*]Renamed the public mod branding to DreamTools.
[*]Updated metadata, Workshop text, in-game UI, logs, loading overlay, preview image and icon for DreamTools.
[*]Kept only the short dt_* console commands to reduce startup reflection work.
[*]Added Client Side / Local, Host / Server and Network / Coop sections in config.
[*]Added colored in-game section headers for easier identification of local, host/server and coop/network options.
[*]Improved in-game window scrolling so lower controls remain reachable.
[*]Improved startup loading with deferred initialization and an explicit guarded Harmony patch list.
[*]Added visible localized loading phases after Apply Mod so the game no longer looks stuck while DreamTools finishes initialization.
[*]Reduced runtime allocations in loot magnet, throttled automatic cooldown resets, removed per-attempt auto attack slot arrays and debounced in-game UI config saves.
[*]Reduced recoverable startup patch failures from red errors to warnings.
[*]Added optional Render Light Safety for the known URP LightCookieManager bounds exception.
[*]Fixed Release build warnings caused by missing game DLL references.
[*]Improved Auto Attack rotation and slot control.
[*]Improved Loot Magnet so stardust can be collected without triggering portals or generic interact actions.
[*]Improved EN/ES/PT language switching from config and in-game UI.
[/list]

[h2]Private Co-op Mode[/h2]
This mod is designed for private lobbies with consent.

[list]
[*]The host should enable [b]Allow Coop Requests[/b] in the Utility tab.
[*]Friends with the mod can press trainer buttons.
[*]Those buttons send requests to the host.
[*]The host applies the action server-side.
[/list]

[h2]Controls[/h2]
[list]
[*][b]F5[/b] - Open/close DreamTools menu.
[*]Resources page - currency, stardust, platinum and unlock tools.
[*]Combat page - god mode, mana, heal, multipliers and local combat helpers.
[*]Auto Attack page - slots, rotation, target priority and range.
[*]Player Utility page - presets, language, loot magnet and profile color helper.
[*]HUD / UI page - Field of View, FPS, ping, pop-up notifications, cooldown notification visibility and optional render light safety.
[*]Map / UI page - map node travel, reveal map and teleport.
[*]Host / Server page - host-sensitive gameplay options.
[*]Network / Coop page - private co-op request controls.
[*]Diagnostics page - runtime hook status, patch state and loading progress.
[/list]

[h2]Console Commands[/h2]
[code]
dt_help
dt_gold <amount>
dt_dust <amount>
dt_stardust <amount>
dt_platinum <amount>
dt_node <index>
dt_reveal
dt_unlock
dt_heal
dt_mana
dt_cooldowns
dt_god <true|false>
dt_damage <multiplier>
[/code]
dt_* command metadata is documented in-game. Startup console registration is skipped to avoid loader scan errors.

[h2]Important[/h2]
[list]
[*]Recommended for single-player or private games with friends.
[*]Do not use gameplay-changing options in public matchmaking.
[*]Make sure everyone in the lobby agrees before using trainer features.
[*]Some options require host/server authority.
[/list]

[h2]Español[/h2]
DreamTools es un trainer para single-player y partidas privadas con amigos. Agrega menú con F5, recursos, multiplicadores, herramientas de mapa, desbloqueo de héroes/skills, idioma EN/ES/PT y modo coop privado donde los clientes piden acciones y el host las ejecuta.

[h2]Português[/h2]
DreamTools é um trainer para single-player e partidas privadas com amigos. Adiciona menu com F5, recursos, multiplicadores, ferramentas de mapa, desbloqueio de heróis/skills, idioma EN/ES/PT e modo coop privado onde clientes pedem ações e o host executa.
