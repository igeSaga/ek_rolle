# Energy Concept for the Municipalities Rolle and Mont-Sur-Rolle

The goal of this project is to develope an energy concept for the two municipalities Rolle and Mont-Sur-Rolle. An important building block of the concept is a database consisting of all buildings with associated information on size, volume, heating system and, finally, an assumption for the total energy consuption.

## Getting Started

The respository contains all R files, required for the computational part of the analysis. The following R markdown files are contained:

- rolle_buildings.RMD: The script covers all steps from reading in geometries of buildings, to the intersection of buildings with relevant metadata and, finally, the computation of a homogenized set of buildings that can be used in all follow up analysis. A map that shows the Result from this first processing step can be found [here](http://geo.uzh.ch/~cderungs/saga/map.html). Figures representing some basic charactersitics of buildings in Rolle are stored [here](https://github.com/igeSaga/ek_rolle/tree/master/output/viz). Finally, an online version of the R script is available [here](http://geo.uzh.ch/~cderungs/saga/rolle_buildings.html)

- rolle_energy.RMD: The script translates area, number of levels and year of construction of buildings into energy-use. A map that shows the Result from this conversion can be found [here](http://geo.uzh.ch/~cderungs/saga/mapEnergy.html). An online version of the R script that produced these results is available [here](http://geo.uzh.ch/~cderungs/saga/rolle_energy.html)

- rolle_summaryStat.RMD: The script is in a preliminary state and thus work in progress. A map that shows a first energy-grid for Rolle can be found [here](http://geo.uzh.ch/~cderungs/saga/mapEnergyGrid.html). An online version of the R script that produced these results is available [here](http://geo.uzh.ch/~cderungs/saga/rolle_summmaryStat.html)

## Authors

* **Curdin Derungs** - *Initial work* - [curdon](https://github.com/curdon)


## License

This project and all incorporated data is property of the HSLU and can only be used upon request.

