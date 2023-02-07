# IntProg_W2

This game is a simulation where balls collide with each other and either form clumps or break each other apart.

Essentially, there is a rock-paper-scissors interaction determined by the size of the clump.

If (size % 3 == 1) then rock (cyan).
If (size % 3 == 2) then paper (orange).
If (size % 3 == 0) then scissors (purple).

When same color clumps collide, they join.

When different color clumps collide, the color that loses the exchange splits apart.
