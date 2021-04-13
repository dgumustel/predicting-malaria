# predicting-malaria

Group project for DSIR, group members: Amir Semsarzadeh, Tarun Nappoly, Umair Evans, Derya Gumustel

---

### Problem statement - Linking dams to human health 
Our goal is to investigate whether the presence, size, and proximity of local dams have an effect on the number of water-born disease cases like cholera or malaria in 1 country or region of the world. 

Null hypothesis: The presence, size, and proximity of local dams do not affect the number of malaria cases in nearby areas.
Alternative: There is some relationship between dam presence, size, and proximity, and the number of malaria cases in nearby areas.

---

### Resources
Readings on the topic: 
Positive and Negative Impacts of Dams on the Environment - 
https://cvc.ca/wp-content/uploads/2011/02/60.pdf
Who’s at risk? sub-Saharan Africa, S.E. Asia, Eastern the Mediterranean, the Western Pacific, and the Americas, fact sheet from the WHO
https://www.who.int/news-room/fact-sheets/detail/malaria#:~:text=Most%20malaria%20cases%20and%20deaths,Americas%20are%20also%20at%20risk.
Malaria around large dams in Africa: effect of environmental and transmission endemicity factors https://malariajournal.biomedcentral.com/articles/10.1186/s12936-019-2933-5#:~:text=In%20the%20present%20study%2C%20the,over%20the%20years%20of%20analysis.

---

### Datasets

[Dams, Poverty, Public Goods and Malaria Incidence in India](https://dataverse.harvard.edu/dataset.xhtml;jsessionid=db62793d82a9902a12f909f985b5?persistentId=hdl%3A1902.1%2FIOJHHXOOLZ&version=&q=&fileTypeGroupFacet=&fileAccess=&fileSortField=date)

Description: The data contains 5 different files, classified by topic. The file india_pov_c81_revise.dta contains variables on the number of dams in each district as well as information about the neighbouring districts. The data set also includes data on local poverty, such as a povertygap measure, the gini coefficient, mean per capita expenditure. The file india_ag_extend contains in addition, data on agricultural produc tion ( value, yield) for major crops and distinguishes between water-intensive and non-water-intensive crops. The file census.dta contains data on the population size and occupation. The file india_public_updown_doc.dta contains data on the availability of public goods such as water access, power facilities and road. The file malaria_code81.dta contains in addition a variable about malaria incidence.

Dataset of 38,000+ georeferenced dams - includes shape files (points and polygons) of dams of all sizes around the world - [paper](https://www.nature.com/articles/s41597-020-0362-5), [Datasets](http://globaldamwatch.org/data/#core_global)

Description: Each of the three core datasets has been developed over many years with a particular focus and methodology. The Global Geo-referenced Database of Dams (GOODD) maps all dams visible on Google Earth satellite imagery globally; it catalogues the geospatial coordinates of 38,660 dams. The Global Reservoir and Dam Database (GRanD) maps the location and attribute data of 7,320 dams greater than 15m in height or with a reservoir of more than 0.1km3. Future Hydropower Reservoirs and Dams (FHReD) maps 3,700 dams that are under construction or in advanced planning stages. Together, these three datasets represent the most detailed, freely available global database of dams and georeferenced information about global dams.
