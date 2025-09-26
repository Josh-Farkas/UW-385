My general idea for my game is a Tetris deckbuilding roguelite, where each cell on a tetris block can have different effects on it, and it's the players job to modify and add effects to different pieces in their 'deck'. The goal is to beat an enemy that's attacking you by placing negative pieces down on the board, for example changing a tile in the background so that if you place a piece there you take damage. The core gameplay loop is buying effects and helpful items in the shop using money you earn during battles, upgrading your pieces, and then fighting a monster.

I've worked on this game in the past and here's a document I had that layed out some of my ideas for the game:


Effect Triggers:
On Clear (When removed from the board)
On Place
When an adjacent cell is cleared
When a piece is placed
When you take damage

Effect Types:
Sword:
On Clear: Deal 1 Damage.
Common

Shield:
On Clear: Gain 2 Block
Common

Dagger:
When an adjacent line is cleared deal 1 damage
Common

Chains:
On Clear: Deal 2 damage for each connected Chain
Common

Vial:
On Clear: Apply a random negative effect
Uncommon

Poison Flask:
On Clear: Apply 1 poison
Common

Prayer:
Like Mantra from STS, when you get enough the board changes or something and you get a big boost, maybe 2x damage or time stop

Cloud:
On Clear: Deal 1 damage for each row below this
Uncommon

Drill:
On Clear: Deal .2 damage for each tile above this
Uncommon

Bomb:
On Clear: Explodes all tiles in a 3x3 area, deals 1 self damage
Rare

Grenade:

Holy Water:
Clears all enemy attacks in a 5x5 area

Other Ideas:
Effect that copies another somehow
Maybe changes into a random effect every time it spawns?

Fragile, means the effect can only be placed once per combat (removed from piece after use)
Status Effects
Block: Block the next X damage taken
Evade: Next instance of damage is avoided and lose 1 evade
Confusion: Rotates your piece uncontrollably
Poison: At the end of turn take X damage
Blindness: Can’t see top X rows of the board

Shop:

Effects:
6 Effect Slots:
1-3: Common
4-5: Uncommon
6: Rare

Pieces:
2 Randomly Generated Pieces
Each cell can have an effect
.01 for rare
If not rare then .05 for uncommon
If not uncommon then .1 for common
