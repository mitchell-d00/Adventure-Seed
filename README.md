<p align="center"><img src="logo.svg" width="96" alt="Adventure Seed logo"></p>

# Adventure Seed

A roguelike in a single HTML file. Pick a setting, a people and a calling, then
cross a galaxy grown from a seed to kill the Hollow King at its centre. Death is
permanent.

## Play

Open `index.html` in any browser. There is nothing to install or build.

To put it online, turn on GitHub Pages for this repository (Settings → Pages →
deploy from the `main` branch, root folder). The game will be served at
`https://<your-username>.github.io/<repo-name>/`.

The game saves in the browser whenever you change maps or close the tab. A save
is deleted when the character dies or wins.

## What is in it

- **3 settings**: Fantasy, Sci-fi and Post-apocalypse. A setting renames
  everything (classes, peoples, items, foes, money, towns, vehicles) and changes
  the look of the page and the buildings, but the rules are the same.
- **A seeded galaxy.** Type any seed and choose 36, 90 or 200 stars. The same
  seed, size and setting always grow the same stars, links, worlds and maps, so
  seeds can be shared. The title screen previews the galaxy as you type.
- **Outdoor and indoor maps.** Every world has an outdoor map in one of six
  biomes, with roads, a landing pad, usually a town, and two or three dens to go
  down into. Dens are caves or built places, two to three floors deep, with an
  alpha and a cache at the bottom.
- **6 peoples**, each with attribute changes and a perk, and **6 callings**,
  each with four abilities learned at levels 1, 5, 12 and 20.
- **6 companions**: a fighter, a fast one, a ranged one, a tough one that draws
  attacks, a healer and a pack animal. One travels with you at a time.
- **3 ground vehicles** for outdoor travel: a cheap one, an armoured one and one
  that crosses water. Your ship carries you between worlds and stars.
- **Towns** with three traders, a dealer in companions and vehicles, and a
  lawkeeper who pays for clearing dens.
- **200 items** and **80 kinds of foe** in each setting, plus savage and alpha
  versions of foes.
- **Day and night** outdoors, doors indoors, a minimap, a list of places to walk
  to, pixel-art tiles and sprites, lighting, and floating damage numbers.

## Controls

| Action | Keys |
| --- | --- |
| Move or attack | Arrow keys, or W A S D; Q E Z C for diagonals |
| Wait a turn | Period |
| Abilities | 1 to 4 |
| Fire a ranged weapon | F |
| Explore indoors, gather loot outdoors | X |
| Rest until healed | R |
| Use stairs, a den entrance or your ship | Enter |
| List of places to walk to | T |
| Board or leave your vehicle | V |
| Star map | G |
| Show or hide the minimap | M |
| Pack | I |
| Character sheet | P |
| Close a window | Escape |

Click a foe to target it, click a distant tile to walk there, or click yourself
to use what you are standing on. On a touch screen a direction pad appears under
the map.

## How the galaxy works

- You start on a safe world at the rim. Danger runs from 1 at the rim to 20 at
  the core, and it sets the level of everything on a world.
- Stand on the landing pad and open the star map to fly to another world of the
  same star or jump to a linked star.
- Leaving a world resets it, apart from dens you have cleared.
- The Hollow King is on the lowest floor of the one den on the core world.

## How the numbers work

- **Strength** adds melee damage, **Dexterity** adds accuracy, evasion and
  ranged damage, **Intellect** adds power and the pool your abilities draw on,
  **Vitality** adds health. Light blades use Dexterity for damage when it is
  higher.
- Armour reduces physical damage by a proportion; blasts from casters are
  reduced much less.
- Sleeping foes are always hit.
- While you ride a vehicle, foes get half as many turns and damage goes to its
  hull. A wrecked vehicle must be repaired in a town.
- A knocked-out companion recovers when you change maps.

## Files

- `index.html`: the whole game: markup, styles, data and script
- `logo.svg`: repository logo and page icon
- `LICENSE`: MIT licence

## License

MIT. See `LICENSE`.
