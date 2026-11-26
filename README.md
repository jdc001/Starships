# Starships (working title)

Version 0.7.3

A one-on-one starship duel game for iPhone and iPad, played in simultaneous turns.

**Play:** https://jdc001.github.io/Starships/

On iPhone, open the link in Safari and choose Share > Add to Home Screen to play it full screen.

## How it plays

Each turn you plot a course, choose one action, then tap ENGAGE. Both ships carry out their orders together for six seconds. The Kesh choose in secret.

- **Course:** tap or drag in space, or pick a tactical order (Strafe, Orbit, Lance, Evade, About, Stop). The dotted line shows exactly where you will go.
- **Action:** Hold (bank weapon charge), Fire (release it when your guns bear), Scan (reveal the board, and yourself), Flank (top speed, no firing). A cloak adds Cloak, Strike (fire then cloak) and Ambush (decloak and fire). A tractor beam adds Tractor.
- **Fold, mines, drones:** Fold teleports you anywhere but takes your weapons offline for two turns. Aft mines drop on top of any action every three turns. The Drone Swarm module launches four point-defence drones for three turns that can shoot down torpedoes.
- **Torpedoes:** Fusion (yellow, balanced), Antimatter (red, heavy but slow and short-ranged), Gravitational (blue, light but knocks the target off course and toward planets). Each mount upgrades Mk I to III.
- **Capacitors:** weapons store up to three charges. A full bank fires a much bigger volley. Hitting a ship that has not spotted you is an ambush for 50% extra damage.
- **Sensors:** you only see the enemy within sensor range, or when they fire, scan or run at flank speed. Otherwise you see their last contact and a circle of where they could be. Nebulae hide ships but blind their sensors and stop shield recharge.

## The galaxy

Six empires share a spiral galaxy, each starting with a sixth of it: the Terran Concord (home to Sol), the Kesh Dominion, the Orrun Hegemony, the Vael Collective, the Thane Free Worlds and the Sylari Choir. The map has 96 sectors in four rings. Core sectors are worth three times a rim sector and are defended by much stronger ships.

- **Contracts:** tap any border sector and choose which neighbouring empire to fight for. Win and the sector changes hands.
- **Difficulty comes from the map:** how deep the sector is, how big the defending empire is, and how far into the campaign you are. Upgrading your ship is how you push into the core.
- **Reputation:** working for an empire raises your standing with it and lowers it with the one you hit. Below -40 an empire refuses to hire you; below -60 it sends its best against you.
- **What reputation buys:** each empire unlocks its own hulls, modules and torpedo warheads. Friendly empires pay patronage after every win, scaled by their size, and allies give shipyard discounts.
- **The galaxy moves without you:** border clashes happen between missions. Any empire above 40% faces a coalition.
- **Winning:** Conquest (an allied empire holds two thirds of the galaxy) or Balance of Power (two or more allied empires each hold at least 25%, together 75%).

Progress saves in the browser after every mission. The title screen adds three save slots, a save code you can copy to another device, options (sound, screen shake, turn length, watch speed, tips) and the privacy policy.

## Files

- `index.html`: the whole game in one file (HTML, CSS and JavaScript, no build step).
