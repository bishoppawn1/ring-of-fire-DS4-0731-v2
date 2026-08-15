# Ring of Fire Game Specification

## Intent

This document is a creative benchmark brief, not a blueprint. It defines the identity and major mechanics of `Ring of Fire` while deliberately leaving balance, presentation, content, and implementation open to interpretation.

A recreation should feel recognizably like the same game, but it should also show the creator's own judgment. Examples below communicate the desired variety and are not exhaustive checklists.

## Core Identity

`Ring of Fire` is an endless top-down arena survival game. The player moves and dashes through increasingly dangerous waves while their weapon automatically aims and fires at nearby threats. Enemies create readable projectile patterns that reward movement, positioning, and build choices.

A run begins with character and difficulty selection. The player fights several normal waves, defeats a boss, visits a shop, and advances to a harder floor. The run ends when the player dies.

## Required Gameplay

- The player can move freely and perform a short invulnerable dash.
- The player's appearance stays simple and does not change with equipped weapons.
- Weapons auto-aim and auto-fire, but have limited range so positioning matters.
- The player has health, brief invulnerability after being hit, and armor that reduces damage without making the player completely immune.
- Projectiles disappear at the arena boundary and cannot accumulate forever.
- Some homing missiles can be destroyed. They turn with momentum and live long enough to cross the arena, allowing skilled players to lead them into the boundary.
- Most enemies roam unpredictably. Behavior-focused enemies, such as rammers, may actively pursue the player.
- Defeated enemies award both XP and uncapped money.
- The arena provides enough open space for dense combat and does not include safe cover that lets automated allies win without player involvement.

## Waves And Escalation

Each floor has four normal waves followed by a boss and a shop. New floors increase pressure through some combination of enemy count, durability, damage, attack complexity, and newly introduced enemy types.

Bosses should feel substantially different from normal enemies. Most of their projectiles should be non-homing so the player's auto-aim is not constantly distracted by missiles. Every fifth floor adds a special boss gimmick, and every twenty-fifth wave features a memorable super boss.

Several difficulty options should meaningfully alter the intensity of a run. Exact scaling and balance are left to the creator.

## Enemies And Weapons

The game should contain a varied enemy roster with visually distinct behaviors. Possible ideas include aimed shooters, homing attackers, laser enemies, accelerating bullets, changing volleys, rammers, and shield-support enemies. Creators may reinterpret or replace these ideas as long as encounters remain varied and readable.

The player should be able to discover weapons with meaningfully different range, cadence, coverage, and tactical use. Possible ideas include a basic firearm, shotgun, rapid weapon, heavy weapon, piercing laser, mines, damaging ground effects, and unusual rare weapons.

Area damage and additional-projectile effects should have sensible limits so they do not erase positioning or overwhelm the game. Enemy projectile damage should scale over time so armor cannot trivialize later floors.

## Characters

Characters should create distinct play styles through meaningful strengths and drawbacks. The intended range includes:

- A balanced all-purpose character.
- A dual wielder who fires twice but gains less from upgrades.
- A fragile engineer whose turrets copy their weapon and upgrades.
- A durable defensive character with weaker offense.
- An explosive specialist focused on area control.

Names, exact modifiers, additional characters, and alternate interpretations are open to the creator.

## Progression

When the player earns enough XP, the game pauses and offers three random base-stat choices. Core stats include weapon damage, percentage-based firing rate, armor, and maximum health. Movement-speed and projectile-speed upgrades are excluded from normal progression.

Extra XP carries across level-ups, and each new level requires increasingly more XP.

Money is displayed as a number, not a bar. It is spent in a shop after each boss. Entering the shop restores health and pauses combat.

The shop should mix weapons, normal stat upgrades, unusual upgrades, rare artifacts, and upgrades with trade-offs. Rare finds should be uncommon but realistically discoverable during ordinary play. Later-floor weapons should generally be stronger.

The shop can be refreshed for a price. Buying an offer immediately replaces that slot with another offer of the same broad kind and a newly determined price, so buying does not leave the shop empty.

## Turrets

Turrets are rare, expensive allies that appear at random arena positions and relocate each floor. They turn toward their most recent target.

Normally, turrets use a fixed basic attack and ignore player modifiers. Engineer turrets are the exception and copy the engineer's weapon and upgrades. Turrets should be useful without enabling a passive strategy.

## Interface And Game States

The game begins on a new-game screen with character and difficulty selection. Death returns the player to this screen.

During a run, the interface should clearly show health, XP, money, level, floor, and wave. Health and XP use separate bars; money has no bar. The game pauses during level-up choices, shops, and other menus so the player cannot be harmed while deciding.

## Creative Freedom

The creator is free to decide:

- Exact numbers, probabilities, prices, and scaling formulas.
- Visual style, animation, effects, sound, and music.
- Names and designs for characters, enemies, bosses, weapons, upgrades, and artifacts.
- Arena presentation and how its appearance changes between floors.
- Menu and interface layout.
- The size of the content roster.
- Additional mechanics that complement the core loop.

Original ideas are encouraged. They should strengthen the game's main pillars: skillful movement, readable projectile pressure, escalating challenge, build variety, and rewarding discoveries.

## Evaluation

A successful recreation should be judged by whether it:

- Is immediately playable and understandable.
- Feels responsive and rewards skillful movement.
- Escalates without sacrificing visual clarity.
- Produces varied builds through characters, weapons, upgrades, and shops.
- Introduces meaningful enemy and boss variety over time.
- Encourages repeated runs through randomness and rare discoveries.
- Expresses a coherent creative interpretation instead of merely matching a list of values.
