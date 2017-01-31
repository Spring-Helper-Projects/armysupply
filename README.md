# Army supply

This implements a supply/food cap, similar to e.g. Warcraft.

There is currently only one kind of supply (so not like e.g. Starcraft where each race has a separate counter).

# Usage

Providing and using supply are both controlled through unit custom params: `supply_granted` and `supply_cost`.
Widgets and AIs can read current supply status through team rules params: `supplyUsed` and `supplyMax`.
