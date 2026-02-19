# What I tried to implement

- `symbol` layers can add an `elevation-offset` property to their layout, which renders the symbol at some elevation relative to the terrain.

# Issues with current implementation

- fill extrusions can appear in front of the ico, even if that is not technically true in 3D space.
    - I think this is okay, but no idea
- overlap calculations are performed in 2D - might be worth replacing KDBush
-
