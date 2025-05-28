# Plastic Cyberpunk NPCs

A FoundryVTT module containing low-CR cyberpunk-themed humanoid NPCs, designed for D&D 5e. These top-down token actors are great for neon-soaked back-alleys, shadowy labs, or dystopian arcologies.

## 🧠 Included NPCs

| Name                    | CR   | Description                                                           |
|-------------------------|------|-----------------------------------------------------------------------|
| Junior Security Guard   | 1/8  | Rookie enforcer with a standard baton.                                |
| Security Guard          | 1/4  | Tactical rent-a-cop with light armor.                                 |
| Security Supervisor     | 1    | Veteran leader with a shock baton.                                    |
| Back-Alley Scrapper     | 1/4  | Cyber-enhanced brawler from the slums.                                |
| Neon Ganger             | 1/8  | Fast and flashy with a glowing blade.                                 |
| Hackrat                 | 1/2  | Hacking-savvy scavenger with shock gear.                              |
| Sparkskitter Drone      | 1/4  | Spider-like construct with electric lash and target-marking signal.   |
| Ironhowl Enforcer       | 1    | Floating orb with arcane pikes and a disruptive kinetic pulse.        |
| Mimetic Rift Node       | 2    | Psychic projection crystal that splinters into illusions.             |

## 🔧 Included Items

| Name                  | Type      | Description                                                                 |
|-----------------------|-----------|-----------------------------------------------------------------------------|
| Baton of Shock Impulse | Weapon   | Compact shock baton that deals bludgeoning and lightning; disables reactions. |
| Shock Staff           | Weapon    | Long staff with electric coils; deals mixed damage and disables reactions.  |
| Zap Disc              | Consumable| Detonates in a 10 ft radius; deals lightning damage and prevents reactions. |
| Neurospike Capsule    | Consumable| Creates a silence zone for 2 rounds.                                       |
| Chaff Bomb            | Consumable| Obscures area and imposes disadvantage on ranged attacks.                  |
| Signal Leech Dart     | Consumable| Marks a target to grant advantage on ranged attacks for 1 minute.          |
| Arc Trap              | Consumable| Triggers lightning damage when a creature steps on it.                     |
| Perfect Loop          | Feat      | Monks repeat their last action with no rerolls — flawless execution.       |
| Indexed Weakness      | Feat      | Marks a foe; unarmed strikes deal extra force damage once per turn.       |
| Shared Circuit        | Feat      | Link with an ally to absorb damage or transfer HP.                         |
| Pulse-Sync Burst      | Feat      | Sync with allies to gain movement and temp HP.                             |
| Care Protocol Override| Feat      | Twice per short rest: heal, stabilize, or resist mental effects.           |
| Harmonic Bloom        | Feat      | Enter a 3-turn trance to buff allies and restore Monk Focus.               |


## 🎯 Installation

### FoundryVTT Manifest URL
https://raw.githubusercontent.com/plasticus/cyberpunk-npcs/main/module.json


1. Open **FoundryVTT → Setup → Add-on Modules → Install Module**.
2. Paste the manifest URL.
3. Enable the module in your world.

### Manual Installation

1. Download this repo as a `.zip`.
2. Extract it into your `FoundryVTT/Data/modules/` folder.
3. Enable it inside your world.

## 🎨 Tokens

Custom 256×256 top-down `.webp` tokens included under:
assets/tokens/


Designed for clarity on VTT battle maps. Transparent backgrounds.

## 🛠️ Development

To edit or contribute:

```bash
git clone git@github.com:plasticus/cyberpunk-npcs.git
Then open in your code editor and update:

    packs/cyberpunk-npcs.db for NPC data

    assets/tokens/ for images

    module.json for metadata