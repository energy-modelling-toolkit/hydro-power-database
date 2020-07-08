 [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
 [![DOI](https://zenodo.org/badge/179688356.svg)](https://zenodo.org/badge/latestdoi/179688356)

# JRC Hydro-power plants database

![map of hydro-power plants](map-location.png)

This dataset is an output of the Energy work package of the Water-Energy-Food-Ecosystems (WEFE) Nexus project at the European Commission's Joint Research Centre (JRC). This dataset has been created for power system modelling purposes and it is based on publicly available sources. This dataset tries to collect some basic information on all the European hydro-power plants. Other related datasets are available in [the JRC Data Catalogue](https://data.jrc.ec.europa.eu/collection/id-00134).

The dataset contains the following variables (documented in the data package JSON):
  - id of the plant
  - name of the power plants
  - installed capacity (and pumping capacity when available)
  - country
  - coordinates
  - typology of the power plant (run-of-river, reservoir based or pumped-storage)
  - nominal head or height of the dam
  - size of the usable reservoir in million of cubic meters
  - maximum storage capacity in MWh
  - link with the GEO, PyPSA-EUR and WRI Global Power Plants databases
  - annual average/expected generation in GWh
  
The storage capacity is reported only when directly available from the source, thus is **not** estimated or derived from the other variables. 

This dataset is released under [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/).

## Discuss & Contribute
If you have any question or comment the best way would be to add a post in the Issues to keep track of open and closed issues/questions.
If you want to contribute please [send me an email](mailto:matteo.de-felice@ec.europa.eu) or submit a Pull Request on this repository. 

## Author and contributors
Here a list of all the people which have personally contributed to this dataset. If you think that your name should be here please send me an email.

   - Matteo De Felice, JRC: main author
   - Konstantinos Kanellopoulos, JRC
   - Ignacio Hidalgo-González, JRC
   - [Kachirayil Febin](https://github.com/febinka)
   - Arnau Cangròs, Catalan Water Agency
   - Hrvoje Medarac, JRC
   - Goran Stunjek, University of Zagreb
   - Goran Krajacic, University of Zagreb
   - Jonas Hörsch, Reiner Lemoine Institut (RLI) and KIT
   - Francesco Careri, JRC
   - Sebastian Busch, JRC
   - André Ortner, MVV Energie and TU Wien
   - Clément Cabot, PSL - Mines-ParisTech
   - [@flacombe](https://github.com/flacombe)
   - [@timtroendle](https://github.com/timtroendle)
   - Antoine Dubois, University of Liège
   
## Coverage

The dataset contains 4127 hydro-power plants. This is a table summarising the installed capacity in GW for all the countries appearing in the database. 

|country                |   GW|
|:----------------------|----:|
|Albania                |  2.0|
|Austria                | 13.6|
|Belgium                |  1.4|
|Bosnia and Herzegovina |  2.0|
|Bulgaria               |  2.9|
|Croatia                |  2.1|
|Czechia                |  1.9|
|Finland                |  2.6|
|France                 | 20.4|
|Germany                | 10.8|
|Greece                 |  3.4|
|Hungary                |  0.0|
|Ireland                |  0.5|
|Italy                  | 19.3|
|Latvia                 |  1.5|
|Lithuania              |  1.0|
|Luxembourg             |  1.3|
|Montenegro             |  0.7|
|Norway                 | 33.2|
|North Macedonia        |  0.6|
|Poland                 |  2.1|
|Portugal               |  6.8|
|Romania                |  6.2|
|Serbia                 |  2.8|
|Slovakia               |  2.5|
|Slovenia               |  1.2|
|Spain                  | 16.1|
|Sweden                 | 13.7|
|Switzerland            | 18.5|
|United Kingdom         |  4.3|

## Sources

The database has been built collecting the information from several other sources and then cross-checking and comparing in case of inconsistencies. The list of the used sources is here:

  - [JRC Power Plants Database (PPDB)](https://zenodo.org/record/3349843)
  - [Global Energy Observatory (GEO)](http://globalenergyobservatory.org/)
  - [PyPSA-EUR](https://github.com/PyPSA/pypsa-eur)
  - [Global Reservoir and Dam Database (GRanD) 1.3](http://globaldamwatch.org/) 
  - [Marktstammdatenregister MaStR](https://www.marktstammdatenregister.de/MaStR)
  - [Open Data Réseaux Énergies](https://opendata.reseaux-energies.fr/pages/accueil/)
  - [OpenStreetMap](www.openstreetmap.org)
  - [Engadiner Kraftwerke AG website](https://www.ekwstrom.ch/startseite.html)
  - [Latvenergo AS website](https://www.latvenergo.lv/)
  - [Gimeno-Gutiérrez and Roberto Lacal-Arántegui, Renewable Energy, 2015](https://www.sciencedirect.com/science/article/pii/S096014811400706X)
  - [Gerritsma, M.K. (2016) Faculty of Geosciences Theses](https://dspace.library.uu.nl/handle/1874/339185)
  - [Swiss committee on dams website](http://swissdams.ch/)
  - [VGB PowerTech e.V. website](https://www.vgb.org/)
  - [EDP website](www.edp.pt)
  - [Drinsko-Limske Hidroelektrane website](http://dlhe.rs/)
  - [Verbund website](https://www.verbund.com/)
  - [Geth et al., Renewable and Sustainable Energy Reviews, 2015](https://www.sciencedirect.com/science/article/pii/S1364032115007923)
  - Wikipedia EN, DE, FR
  - [Karin Salevid, Uppsala Universitet, 2013](https://uu.diva-portal.org/smash/get/diva2:661286/FULLTEXT01.pdf)
  - [Vattenkraft.info](https://vattenkraft.info/)
  - [The United Nations Economic Commission for Europe (UNECE) website](http://www.unece.org/)
  - [Statkraft website](https://www.statkraft.com/)
  - [Salini-Impregilo website](www.salini-impregilo.com)
  - [HEP group website](hep.hr)
  - [Spanish Ministry of Agriculture, Fisheries and Food website](https://www.mapama.gob.es/)
  - [Comité Français des Barrages et Réservoirs website](http://www.barrages-cfbr.eu/)
  - [JP „Elektroprivreda HZ HB website](https://www.ephzhb.ba/)
  - [SSE website](https://sse.com/)
  - [WaterGenPower website](https://www.watergenpower.eu/)
  - [Compagnia Valdostana delle Acque website](http://www.cvaspa.it/)
  - [Fingrid website](https://www.fingrid.fi/)
  - [HE Đerdap website](http://www.djerdap.rs/)
  - [Vattenfall website](http://www.vattenfall.se/)
  - [Pöyry PLC website](https://www.poyry.com/)
  - [Innogy website](https://www.innogy.com/)
  - [Dravske elektrarne Maribor website](http://www.dem.si/)
  - [Hidroelektrarne na Spodnji Savi website](http://www.he-ss.si/)
  - [Savske elektrarne Ljubljana website](http://www.sel.si/)
  - [Kemijoki website](https://www.kemijoki.fi)
  - [NVE website](https://www.nve.no/)
  - [Regione Sardegna website](https://www.regione.sardegna.it)
  - [ENAS Regione Sardegna website](http://www.enas.sardegna.it)
  - [GHT Engineering website](http://www.ghtengineering.it)
  - [TPF Ingenerie website](https://tpf.eu/)
  - [Bissi Holding website](http://www.bissiholding.com)
  - [Burgo group website](https://www.burgo.com)
  - [Edison website](https://www.edison.it)
  - [Italgen website](http://www.italgen.it/)
  - [Eneco website](http://www.eneco.it/it/home.html)
  - [IREN Energia website](http://www.irenenergia.it)
  - [Tirreno power](http://www.tirrenopower.com)
  - [ČEZ website](https://www.cez.cz)
  - [ČEPS website](https://www.ceps.cz/cs/)
  - [ESB website](https://www.esb.ie)
  - [Charlotta Canzler, THE ECONOMICS OF SWISS HYDROPOWER PRODUCTION](https://ivm.vu.nl/en/Images/Canzler_Charlotta_-_Thesis_Charlotta_Canzler_PDF_tcm234-352241.pdf)
  - [UK Energy Watch website](http://www.ukenergywatch.org)
  - [hydrelect.info](http://www.hydrelect.info/)
  - [Digitális Tankönyvtár](https://www.tankonyvtar.hu/en)
  - [Hidroelectrica](www.hidroelectrica.ro)
  - [Kalivac HPP](http://kalivachpp.com/)
  - [Ayen](http://www.ayen.com.tr/eng/)
  - [International Hydropower Association](https://www.hydropower.org/)
  - [НЕК ЕАД](https://vec.nek.bg/)
  - [E-Control](www.e-control.at)
  - [UGT](https://www.ugt.es/)
  - [Kesh](http://kesh.al/)
  - [Andritz](https://www.andritz.com/group-en)
  - [Devoll Hydropower Sh.A](www.devollhydropower.al)
  - [Enti Rregullator i Energjise](https://ere.gov.al/)
  - [Catalan Water Agency](http://aca.gencat.cat/ca/inici)
  - [Electricité d'Emosson SA](http://www.emosson.ch)
