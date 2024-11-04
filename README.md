# Lab-10

1. How does A* pathfinding calculate and prioritize paths?

It starts at a specific node and tries to find a path to the goal with the smallest cost.

2. What challenges arise when dynamically updating obstacles in real-time?

The challenge is running the prorgram as the pathfinder will change its course if something is added or gotten rid of.

3. How could you adapt this code for larger grids or open-world settings?

By adding more grids and adding vectors and obstacles that the pathfinder will recognize in engine.

4. What would your approach be if you were to add weighted cells (e.g., "difficult terrain" areas)?

My approach to add weighted cells would be to plan out the placement of the grid and then try to add obstacles of what I would envision the terrain to be like.
