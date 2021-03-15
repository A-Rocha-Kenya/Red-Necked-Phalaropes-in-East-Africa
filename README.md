# Red-Necked Phalaropes in East Africa
Review of the red-necked phalarope sightings in East Africa and discussion of the influence that the extreme positive Inverse Ocean Dipole played in the afflux of Red-necked phalaropes on the Kenyan Coast in February 2020.

![Photo](Media/RN5_6728.jpg)
*More than 3'000 Red-necked Phalaropes were observed 2 km off the Kongo estuary on the he shore on 9 February 2020.*

## Sigthings in East Africa
We reviewed existing literature and perform an exhaustive search of all previous records for this species across East Africa (Ethiopia, Kenya, Tanzania, Uganda), as recorded in literature (East African Bird Rarity, Scopus, African Bird Club Bulletin) and on citizen science databases (eBird, 2020; KenyaBirdMap, 2020). [`sightings.csv`](R_code/sightings.csv) gathers all data found.

![Photo](figures/summary_sightings.png)
*Summary of sightings in East Africa (Ethiopia, Uganda, Tanzania, Kenya).*


## Net Primary Productivity in East Africa
(Oceanic) Net Primary Productivity (NPP) is a usefull proxy for the presence of planktonik species on which Red-necked phalaropes feeds as it can be measured with remote sensing (sattelite). We used measurement of NPP during normal and extreme Inverse Ocean Dipole year to illustrate the variation in food availability for Red-necked Phalaropes. 
The NPP data are computed with the Vertically Generalized Production Model (VGPM) algorithm (Behrenfeld & Falkowski, 1997) retrieved from [ocean.productivity](http://sites.science.oregonstate.edu/ocean.productivity/) (O’Malley, 2020) and analyzed with [Google Earth Engine](https://earthengine.google.com/) (Gorelick et al., 2017). A [interactive and comparative map of NPP between years](https://rafnuss.users.earthengine.app/view/net-primary-productivity) is available.

![Photo](figures/map_npp.png)
*Map of Net Primary Productivity (NPP) averaged for Jan-Mar on the western Indian Ocean. In “usual” years (1997-2021 – average of all years available), a bloom is visible offshore of the Kenyan-Somalian border. However, during years with a strong positive IOD (1998 and 2020), this bloom is absent.*

## Analysis

The analysis of these data and the generation of the figures was performed in R. [The corresponding markdown file](R_code/Red-necked_Phalarope_publication.html) is available. 
