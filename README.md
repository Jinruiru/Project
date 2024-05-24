＃Project

The aim of this project is to study the relationship between unemployed population and the incidence of crime in Leeds. The repository contains data on the number of usual residents and the history of unemployment from the UK 2021 Census, records of crime occurring within West Yorkshire, Leeds area shape file, and .ipynb notebook containing code for the data analysis process. In particular, the “Lower_layer_Super_Output_Areas_2021_EW_BFE_V9_-3647710721716634062.geojson” data is too large and it will take a long time to download, so I've extracted the shape file for the Leeds area separately from the data processing, so that users can use the “Leeds.geojson” data directly.

Previous research has proposed that there is a dynamic relationship between crime and unemployment in particular groups(Massourakis, et al, 1984). In order to examine whether there is a relationship between the unemployed population and the occurrence of criminal behavior in Leeds, data on the number of unemployed people of all types in each area of Leeds in 2021 was downloaded, and the percentage of never worked people was calculated for each region. Then, compare these data with the number of crimes and perform a correlation analysis using Spearman’s rank model. The results of the analysis can help local governments make decisions to control the occurrence of local crime.

The result shows that there is a positive correlation between the number of never-employed people in an area and the incidence of criminal activity in that area. Therefore, in order to maintain social harmony, more attention should be paid to the prevention of crime in areas with a large number of unemployed people, and attention should be paid to the adoption of measures to encourage employment.

Special note: because the “Lower_layer_Super_Output_Areas_2021_EW_BFE_V9_-3647710721716634062.geojson” data is too large to submit it to Turnitin, please use the “Leeds.geojson” data directly.

Reference:
Massourakis, M., Rezvani, F. and Yamada, T. 1984. Occupation, Race, Unemployment and Crime In a Dynamic System. Cambridge, Mass: National Bureau of Economic Research.
