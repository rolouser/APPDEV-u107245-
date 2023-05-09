` `***OBTAINING A  HYDROGRAPHIC ACCOUNT THROUGH THE USE OF A SOFTWARE TO BE TRADEDTO  THE "ARCGIS AND THE USE OF A FREE RE SOFTWARE"S A GA".  C A SO DE ESTUDIO MUNICIPALITY OF PORCESITO, ANTIOQUIA***  

Brian Steve Castro Benavides Cadastral  

and Geodesist  Engineer 

Student of specialization in geomatics Universidad Militar Nueva Granada    

Bogota, Colombia   U3101343@unimilitar.edu.co 

SUMMARY   

The geographical locationof Colombia, the geomorphological conditions and The country, together with the abundant water supply, make the country an ideal territory for  

` `carrying outmulticriteria studies and analysis of the environment, and for the   anthropological impact  of the mediumand longterm.   

Due to the technologicalvance both in soft w are licensed s of  difer e nte s  co s to s  as it e s Arcgis and  also of software libre de cod i fication gratuita  and  Open to be installed from the intern et, the analyses mentioned abovecan bemodeled, dynamically reflected in a wide range of the same range.  As a pr o fesionales in geomatics, with the theoretical and  practical criterion  s the need to apply comparation methodologies, which  cumplan normativeand technical criteria, specifying the way of dealing with the spatial informationl   , taking into account how to obtain the softwar e, installation and   handling, in order to give a concept of the same depending on the is c enary of the pro and ectos to work and el objectivevo by the cual is usedor any of the p r r Ograms. To make the applied comparison of  the result of hydrographic analysis of basin obtained with the do s software, it was implemented for a zone of the  municipality of Porcesito of the department of Antioquia,   s provided with data from  the zona as it son thedigital models of elevation and base cartography.   

Palabras clav e: Cuenca, área hidrográfica, caudal, SAGA, Arcgis.  

ABSCTRACT   

The geographic location of Colombia, the geomorphological and terrain conditions,  together with the abundant water supply, make the country an ideal place to carry  out multi-criteria and  varied analysis studies for decision-making in environmental  projects with short anthropomorphic impact, medium and long term.   

Due to the technological progress of licensed software of different costs, Arcgis and  also offers free and open coding software  to be installed from the internet, the  analyzes mentioned above can be modeled, dynamically expressed  in a wide range  of them.  As professionals in geomatics, with the theoretical and practical criteria  arises the need to apply comparison methodologies, which comply  with normative  and technical criteria, specifying the way to treat spatial information, taking into  account how to  obtain the software, installation and management, in order to To give  a concept of the same depending on the scenario of the proj ects to work and the  objective for which one of the programs was used.  In order to make the applied  comparison of the result of hydrographic analysis of basins obtained with the two  software, it was implemented for an area of the municipality of Porcesito of the  department of  Antioquia, supported with data of the zone as they are the digital  models of elevation and base cartography .   

Ke y words: Basin, hydrographic area, flow, SAGA, Arcgis.    

INTRODUCTION   

Se utilizan diversos soft w are par a  obtener  c uencas hidrográficas, ¿Qué sería el result a l compare a soft w are licensed, which has specific libraries and complements with a soft w Is it free   of free development,  contemplating factors such as time, complejidad of the  procedimiento and development  of the  same?, having as a foundation theoretical tools and withthe current  a v ancesof l a Geomatics  , itis imperative to make an analysis of these means, and  thus to focus  them on the environment, and on the particular of thehydrological cycle  and in obtaining a basin.   

The present study seeks to applythe tools acquired in a discipline such as geomatics, through the systems of geographic information, digital image processing, mapping of network analysis, among other bases of knowledge and purpose   To make a comparison of dos software known, but focused onaspecific productthat is the obtaining of basins.    

ARCGIS DESKTOP 10.4: 

ArcMap and ArcGIS  Pro, the two primary desktop applications for  PRorGIS professionals, are part of ArcGIS for Desktop. ArcMap and  its accompanying application, ArcCatalog, as well as ArcGlobe and ArcScene, work witha view to a GIS performance or  performance. This s  applications s on the basis of es te system of aand uda. Marco, P.P.  (2011, October). 2 

A link of Arcg is on another s soft w are, is the technical soporwhich offers c obertura continua every day of the week and   with fast and efficient responsess, addslmente the applications  s v  A modi ficando depending on the needs of the  user and the market. Due to the  name and  reputationof the developerESRI has wide diffusion and is well knownin the market.    

Its main and most important and  most of having used it prior to the  exercise is the cost of both the softw are, and the training of each of its modules for optimal use.   

2\.3 PREPARATION OF INFORMATION 

- It was usedor a DEM ASTER par a zona with a spatial resolution of 5 meters of pixel, as a base input for obtaining the cuencas.   
- For the calculation of l flow,  s e utilizo the information of the models of precipitation and evapotranspiration of the estaciones hidrometeorological of the IDEAM for the year 2015.   

2\.3.1 Obtaining a river basin by meansof  A rcgis 

The methodology for obtaining a micro-basinin Arcisbased on the size of pix that of a digital elevation mode(DEM).    

` `The   delimationof Arc g is carried out with the DEM prev iamente loadedgado and was openedArcToolbox, with the following route:   

ArcToolbox > Spatial Analyst Tools >   Hydrology > Fill   

This tool is filling, takes the raster and removes  all the gaps, ie s  pixeles null or without information, because in a  superficie in the modeling of the real vida, the account  covers  all thearea that you want to study.   

2\.3.2Obtaining ariver basin by means ofSAGA   

It is loaded g o the Digital Model of elevation, which is the m ismo u sadoto the  elaboration in Arc g is, it can be aclalarar that SAGA admits c arg ar only l os archivos .sgrd, parto it followed the ruta:  

File / Grid / Load   

As the DEM can have huecos or points of vacio without information, SAGA catalogs the   

raster information such as a pr or hydrological pipeline viable,  ie s a model, to obtain continuously the information of all elevations s  is used or the tool "Fill Sinks" referred to below:  

Geoproccessing / Terrain Analisys /   

Preprocessing / Fill Sinks (Wang Liu)   

Since  only theDEM loadgado was available, the following window opened:  

The output of   yourproduct is generated in that format. Atthe time of savingdar you can exportar as an archivo formato shape.   

2\.3.3Average flow  calculation 

With regard  to the es timation of the  caudal medio, the area of the accounts obtainedby means of the two  softwares, and the   Raster of precipitation and evaporation annual par  to the  region of the study area, was used in order to analyze  zar si hay una d iferencia significativ a in the r esultados of the flows obtained, making the clarification that has and diversas formulas and mode l aciones to make the calculation of theflow of a basin. As the  objective of the development press to make a  comparisonbetween the two software, a statistical estimate is  made to obtain weighted values and to   be able to apply in order to   Direct the formula for calculatingthe flow rate. Therefore with the statisticsobtained s  eapplied:  

3\.1451E-05 \* AC \* (PP - PE) Donde:   

- -AC= Area of the Cuenca.   
- PP= Average of the  precipitation.   
- P= Average of the  evaporación.   

Taking as valor of the balance   

hydrologicalpair to the  zona of study el obtained from the IDEAM for the  year 2017.   

***RESULTS*** 

In this section youcan see the final obtaining  of the   c uenca generated from each of the softwareware usedmentioned above.   

\### 3.1 Basin obtainedby the software  ARCGIS  

The digital elevation model of the zona obtained by applying the filling tool to have a  surfy, with continuous information and with which it  was possible to obtain the cuenca in ARCGIS is apreci  a in Figure 11.   

In relationto the direction of the  flowby means of "flo w  direction" the image generada por el software se evidencia in Figure 12, m i i ss that the calculation of accumulation ofthe flow med i Before  "flow accumulation" can be seenin Figure13. On the other hand, s e generated the construction of the water red, in shape format   (fig. 14).    

Finally, the resulting basincan be shownin Figure 15.    

3. Flow calculation   

The calculation of the caudal medio is usedor   

` `the for mula  presented in the method l ogía, and using the v alores med i os de precipitation evapotrans  piration med i a para l a zona, using data from the climatological

seasons of  l IDEAM 3.    The significant differencebetween the differences can be identified  . 

4. Comparison of the software  

` `Visual:  Figure 22 shows the graphic comparisontoeach of the uses used, there are clear differences in terms of definition and detail. Well,  with the use of Arcgis better definition and  more and ornumberof accounts, while SAGA generalizes both in these respects. Similarly in the network of drains cr eada by Arcgis found both ma and or consistency and number compared to the network of drains obtained with SAGA.   

Statistics: Thepercentages  of variationare significantlyhigh( Table, which means that no model guarantees the effectiveness of the  process, although, in the visal verification, it is possible to distinguish the superiority of Arcg   It was expected that the sum of allthe  caudalis of both processes weremun and  similar, due in the first instance to the area covered by the DEM and   to the v alores of evapotranspiration  and   precipitation, although it has also beennoted that the ma and oria of the  valuesof caudal for theaccountsobtained by SAGA are mu and  similar (observar figure 23), and  as they are not homogeneous areas, the attitude  and  precision of the same is questioned  by not having a modelor reference para poder compare  them, and the algorithm us ado by SAGA to obtain áreas.    

***CONCLUSIONS***    

In carrying out the  comparative analysis, the objective of being able to make a comparison between the two programmes, in terms of statistical and indication, was strengthened,which made it possible to achieve a comparison between the two programmes. Weaknesses and weaknesses of  eachof the programs s  a compara r, and knows r so in determinado moment which e s  el best s oftware utilizar.   

The most complete software in terms of quality and product,   is guaranteedto a more detailed below, and  can becarried outwith its results of  analysis of more quality, precision   and xattitude, and in Part VIsual presents procthose more elaborate.   

However, it is not recommended that the softwareisArcgis for activities thatrequire premura, ni parto people who are starting in geomatics orgeographic information systems, you must have a minimum basic  To be able to operate it and  obtain the desired products,  in addition to itsoperations  and  tools that, although they are automatic processes, can become complex  and costly for  new users.   

The softwareware SAGA presenta less detailed products  con r with regard to  Acgis, a  few large ones is not recommended its uso, dueto the generalizationof sus products, thus being a good option for small scales  and  have an approved referenceonthe different areas of study.   

The softwareware SAGA, es much easier to handlefor people who do not have manyknowledge of GIS, in the case of the c uencas only required to obtain  the DEM,  and in this way you can obtain the products in less than three steps,   saving time and  providing users with a toolthat is easy to understand and  use.   

In the analysis of indicators, the  softwis best suited to determina r cuencas es ARCGIS, however,in the final balanceobtu v o this ventaja por little; the  cual we are ableto have two options at the timeof  realizar works related to basins, as long   as it isan analysis of the detail, the execution time and the  costs of the proand ecto. The user will be able to carry outan analysis of these parameters and    thus decide which program he uses  the most.   

SAGA is a goodchoice for studentswho are not very large, reconnaissance or reconnaissancewith a small budget, and which has a large rangeof useful libraries and  tools,  and as in the  As a study, it is even a good input for a realizationof comparative studies if it is required, taking into account that to be an open sourc e program is andvolucionando constantly.   

On the other hand if you have  the r ecurso s  to develop any type of pro and ecto the most aconseejable will be used r  Arcgis, which guaranteesa muand good product,  and  management in different s  ba s e s of  data s and fo r Matos.    

***REFERENCES***  

- Corporación AutónomaRegionala l de  Cundinamarca CAR. (2010).  Updatingof the Surface WaterSupplyfor the Basins.  Up to Fifth Order for the Jurisdiction of CAR. Bogotá: CAR.   
- HIMAT. Institute of Hydrology, Meteorology and Land Adequacy.  (1985). Inventario de Cuencas  Hidrográficas en Colombia. III Congreso de cuencas hidrográficas en Cali-Bogotá.
- -LopeZ, J.  and Delgado, P. (2009, September).   "Parametric Characterization of the Basins". Presented in Jornadas sob r e Hidrología de Superficie en Tener i fe, Santa Cru z de Tenerife,Spain.   
- Marco, P.P. (2011, October). "Methods of Interpolationion in Arcgis 10".  Presented in UNAM Geography, Mexico City, Mexicoico.   
- US Army Corps of Engineers,  Hydrologic Engineering Center.  (2013). HECGeoHMS  
