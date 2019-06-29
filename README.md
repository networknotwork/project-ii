# project-ii

## Proposal
A multi user browser game where 2+ players make characters that fight turn-based to the death.
Before a match, players create or choose a character.
Each character has a name, weapon of choice, and 20 health.
On victory, the character's health is reset to 20.
On death, the character's name is added to a graveyard and the character is deleted.

### Weapons:
Fist (1 damage, hope you aren't blocked)
Dagger (1-4 dmg, can be thrown)
Sword (1-6 dmg)
Axe (2-8 dmg)
Spear (increased base range, blocks can't counterattack, 1-6 dmg)
Bow (20 arrows, can't attack close range, 2 damage)

### Character actions during a fight include:

Attack (Deal weapon damage to opponent)
Disarm (Chance of dropping opponent's weapon, make them use Fist)

Block (Mitigate opponent weapon damage, chance of counterattack)
Dodge (Attempt to make opponent miss)

Pursue (Close the gap between characters, guarantee Retreat fails)
Retreat (Increase the gap between characters if successful. Pick up any dropped weapon.)