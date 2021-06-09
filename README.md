# tbcc-moonkin-dps-simulator
This repository hosts (mainly) Jupyter notebooks which simulate Moonkin DPS for WoW - The Burning Crusade Classic

At the moment, the notebooks are separated for each gear configuration. At some point, one big notebook checking all cases (including trinkets) may summarize it all.

There are 2 notebooks : 
- dps_generator.ipynb : simulate a sizeable amount of fights to estimate an average DPS for the provided stats and specials (Trinkets _TBD_, Chaotic Skyfire Diamond, Spellfire and Spellstrike set bonuses). By default, it's a 90s fight length.
- coefficient_calculation.ipynb : data tools to calculate the stats coefficient and visualize the importance of each stat.

# Todo-list :
- code each trinket
- include Spell haste
- include mana pool management
