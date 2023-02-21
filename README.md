# Climbing Mount St. Helens
An off-trail pathfinding feature app that needs to find the most hiker-friendly trail for an arbitrary terrain called Skamina hiker GPS II. 

## Skamina Hiker GPS Improved
The Skamania II GPS’s helps the hikers to find the optimal path navigating from start to goal in the arbitray terrain identified as bellow:
- Tiles with heights [0-255]. 
- Cost to move determined by heights of original $h_0$ and new $h_1$ tile. 
- Chebyshev (chessboard) motion allowed.

### Exponential Cost Function: $e^{{h_1} - {h_0}}$



## The Program fulfills the following requirements:
1. Evalute heuristic and prove it is admissible
2. Implement heuristica and code A*
3. Test againts seeds 0-4(inclusive, allow +/- 0.3 for rounding errors)
    * Seed 0: 241.55253710831192
    * Seed 1: 238.5060683830129
    * Seed 2: 236.667690049357
    * Seed 3: 422.01798243905006
    * Seed 4: 254.34464507852198
4. Implement an A* variant
