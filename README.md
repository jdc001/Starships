# Starships (working title)

Version 0.9.4

A squadron-scale starship combat game for iPhone and iPad, played in simultaneous turns.

**Play:** https://jdc001.github.io/Starships/

On iPhone, open the link in Safari and choose Share > Add to Home Screen to play it full screen.

## How it plays

You take up to three ships on each mission. Each turn you give every ship a course and one action (or hand it to an AUTO captain), then tap ENGAGE. Every ship on both sides carries out its orders together for six seconds. The enemy chooses in secret.

- **Course:** tap or drag in space (+ WAYPOINT adds up to five stops; tap the last one to brake to a stop there facing the target), or pick a tactical order (Strafe, Orbit, Lance, Evade, About, Stop). The dotted line shows exactly where you will go.
- **Action:** Hold (bank weapon charge), Fire (release it when your guns bear), Scan (reveal the board, and yourself), Flank (top speed, no firing). A cloak adds Cloak, Strike (fire then cloak) and Ambush (decloak and fire). A tractor beam adds Tractor.
- **Map:** pinch to zoom in or out, or tap MAP to see the whole battlefield.
- **Squadron:** tap a ship or its button in the fleet bar to select it. Tap an enemy, or use ◀ ▶ on the target card, to set its target; FOCUS keeps its guns on that target, FREE lets them fire at anything in reach. Your ships share sensors.
- **Jump, mines, drones:** Jump opens an aperture and brings the ship out anywhere you tap, but takes its weapons offline for two turns. Aft mines drop on top of any action every three turns. The Drone Swarm module launches four point-defence drones for three turns that can shoot down torpedoes.
- **Railguns:** the longest-ranged weapon. Slugs fly straight, so fast, jinking ships can dodge them.
- **Torpedoes:** Fusion (yellow, balanced), Antimatter (red, heavy but slow and short-ranged), Gravitational (blue, light but knocks the target off course and toward planets). Each mount upgrades Mk I to III.
- **Capacitors:** weapons store up to three charges. A full bank fires a much bigger volley. Hitting a ship that has not spotted you is an ambush for 50% extra damage.
- **Sensors:** you only see the enemy within sensor range, or when they fire, scan or run at flank speed. Otherwise you see their last contact and a circle of where they could be. Nebulae hide ships but blind their sensors and stop shield recharge.

## Ships and roles

| Hull | Role | Strengths and weaknesses |
|---|---|---|
| Kestrel | Escort | Cheap all-rounder you start with |
| Wasp | Skirmisher | Very fast, fragile; empties its swarm and torpedo racks and runs |
| Lander | Assault transport | Tough and slow; needed to capture planets and starbases |
| Warhound | Gunship | Fast, heavily armoured, every gun forward |
| Halberd | Line ship | Balanced, beams cover almost every angle |
| Longbow | Artillery | Twin railguns and the best sensors; lethal at range, helpless up close, so it jumps or cloaks when caught |
| Leviathan | Capital ship | Slow and enormous, guns in every direction, most modules |

Damage stays with a ship after a mission and costs credits to repair. A destroyed ship becomes a wreck until you pay to salvage it. You can own five ships.

## Missions

- **Territory:** Strike (destroy the squadron), Capture Planet (destroy three defence batteries, then hold a Lander in low orbit through the end of two turns), Capture Starbase (disable it, then hold a Lander alongside).
- **Pay only:** Raid Planet (destroy the batteries), Escort Convoy (get at least two of your client's three freighters across the map), Intercept Convoy (destroy escorted freighters before they cross the map, paid per kill), Assault Starbase (destroy it outright).
- **Defence:** Defend Planet and Defend Starbase are offered by a sector's owner when a neighbour threatens it. Lose and the sector falls.

## The galaxy

Six empires share a spiral galaxy: the Terran Concord (capital Sol), the Kesh Dominion (Khessaru), the Orrun Hegemony (Grul Anvil), the Vael Collective (The Bloom), the Thane Free Worlds (Freeport) and the Sylari Choir (Choirhold). The map has 96 named star systems strung along the spiral arms and joined by hyperlanes, and each empire's territory grows out from its capital, so borders follow the stars. Every system has a type (shipyard, trade hub, forge world, fortress world, ocean world, ancient ruins, nebula haven, frontier outpost and more), a population and a description, and battles there are fought over that kind of world. Core systems are worth three times a rim system and are defended by much stronger ships.

- **Special systems:** shipyards (ships 3% cheaper each), trade hubs (patronage +10% each) and forge worlds (repairs 10% cheaper each, up to 40%) help you while an empire friendly to you (+25) holds them. They show as gold-ringed stars.

- **Contracts:** tap any border system to see the missions on offer from each neighbouring empire, and the defence contract from its owner. Then pick your squadron in the briefing.
- **Difficulty comes from the map:** how deep the sector is, how big the defending empire is, and how far into the campaign you are. Contracts also keep pace with your three best ships. Building a stronger squadron is how you push into the core.
- **Reputation:** working for an empire raises your standing with it and lowers it with the one you hit. Below -40 an empire refuses to hire you; below -60 it sends its best against you.
- **What reputation buys:** each empire unlocks its own hulls, modules and torpedo warheads. Friendly empires pay patronage after every win, scaled by their size, and allies give shipyard discounts.
- **The galaxy moves without you:** border clashes happen between missions. Any empire above 40% faces a coalition.
- **Winning:** Conquest (an allied empire holds two thirds of the galaxy) or Balance of Power (two or more allied empires each hold at least 25%, together 75%).

Progress saves in the browser after every mission. The title screen adds three save slots, a save code you can copy to another device, options (sound, screen shake, turn length, watch speed, tips) and the privacy policy.

## Files

- `version.json`: the current version number. The game checks it on start and offers to update when it's newer than the copy the device has cached. Bump it together with `VERSION` in `index.html` on every release.

- `index.html`: the whole game in one file (HTML, CSS and JavaScript, no build step).
