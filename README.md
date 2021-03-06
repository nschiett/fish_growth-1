# fish_growth
Growth parameters estimation of coral reef fishes

## Variable description

### *otolith_data_complete_10_07_2019.csv*

* `family` Family
* `genus` Genus
* `species` Species
* `id` ID of the fish
* `agei` Age *i* (*years*)
* `radi` Otolith radius at age *i* (*mm*)
* `agecap` Age of the fish at capture (*years*)
* `radcap` Radius of the otolith at capture (*mm*)
* `lencap` Length of the fish at capture (*total length, mm*)
* `l0p` Length of the fish at hatching (*mm*)
* `r0p` Radius of the fish at hatching (*mm*)
* `li` Length of the fish at age *i* (*mm*)
* `biomass` Biomass of the fish (*wet biomass, g*)
* `location` Location of the sampling
* `observer` Name of the person who realized the otolith reading

## Miscellaneous remarks

* For the variable `radi` there are some *NA* when the `agei` is equal to 0. This means that for the individual we were not able to estimate this value on the otolith. In the analysis it's possible to estimate this value by taking the mean of the other individuals of the same species.

* Some of the fishes came from fish markets. In this case the `location` is filled with the name of the island where the fish was bought, even if the fish has been caught in another island.

* Maybe we can define weights according to the age of the fish?