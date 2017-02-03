# Army supply

This implements a supply/food cap, similar to e.g. Warcraft/Starcraft2.

There is currently only one kind of supply, so it has more in comman with Starcraft 2 as opposed to the more robust/complicated system in Starcraft: Brood War where each race has a separate counter.

# Usage

Providing and using supply are both controlled through unit custom params: `supply_granted` and `supply_cost`.

Widgets and AIs can read current team supply status through team rules params: `supplyUsed` and `supplyMax`.

The supply cap and intrinsic supply can be read through game rules params: `supplyCap` and `supplyIntrinsic`.

# Visuals

There are 3 UI widgets included. The resbar is a traditional metal and energy bar with a bar that also displays supply. The resbar is rather advanced in the way that it provides the supply display. There are several colors on the bar itself. 
* Grey is total supply
* Green is available supply 
* Red is used supply.

The separated widgets (Energy/Metal/Supply display) are all text based. While Metal and Energy are not explicitly needed in this context, they are provided so that you will hvae a consistent set of UI widgets to work with.
