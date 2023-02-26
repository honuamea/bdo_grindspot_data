# bdo_grindspot_data

This repository contains damage values used for spotbreaking of BDO grindspots, eg determining:
* Mob DR
* AP Cap
* AP Cap Multiplier

The data here is generally both saved as a side effect of and reprocessible by a custom 'spotbreaker' toolchain for manual data collection. This tool may or may not be released separately at a later date.

CSV files are arranged in the following format:<br>
\# Optional first line explaining the config used for the testing<br>
AP, min_observed_dmg, max_observed_dmg

The referenced JSON files detailing character specs may or may not be released as part of this repository in the future. They are primarily used as config inputs to the 'spotbreaker' tool mentioned above.
