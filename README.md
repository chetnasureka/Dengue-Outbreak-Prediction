# Forecasting-Disease-Risk-for-Increased-Epidemic-Preparedness
Predicted the break out of Dengue that is likely to occur using Negative Binomial Model, Support Vector for Regression, Week and Month wise Time Series, Analysis using Holt Winter's model, Augmented Dickey-Fuller Testing and Neural Networks tested against cities of San Juan and Iquitos.

The project code is an R Markdown file. The packages that need to be installed are as follows:
1. readr
2. GGally
3. zoo
4. mice
5. lubridate
6. Boruta
7. ggplot2
8. dplyr
9. plot_ly
10. MASS
11. e1071
12. tseries
13. TTR
14. Forecast
15. devtools
16. neuralnet

Kindly note the following while running the markdown:
1. Some version of R don't display the plots in the markdown. Rerunning chunk or running on console will fix this.
2. Some data frame outputs are partly hidden. A small black play button in 'chunk' output will display the complete
   result.
3. Boruta feature selection takes about 5-10 minutes to run. 
4. Some plots could not be renamed because the function did not have parameters to change it.

DataSet:<br/>

   1. city – City abbreviations: sj for San Juan and iq for Iquitos<br/>
   2. week_start_date – Date given in yyyy-mm-dd format<br/>
   3. station_max_temp_c – Maximum temperature<br/>
   4. station_min_temp_c – Minimum temperature<br/>
   5. station_avg_temp_c – Average temperature<br/>
   6. station_precip_mm – Total precipitation<br/>
   7. station_diur_temp_rng_c – Diurnal temperature range<br/>
   8. precipitation_amt_mm – Total precipitation<br/>
   9. reanalysis_sat_precip_amt_mm – Total precipitation<br/>
   10. reanalysis_dew_point_temp_k – Mean dew point temperature<br/>
   11. reanalysis_air_temp_k – Mean air temperature<br/>
   12. reanalysis_relative_humidity_percent – Mean relative humidity<br/>
   13. reanalysis_specific_humidity_g_per_kg – Mean specific humidity<br/>
   14. reanalysis_precip_amt_kg_per_m2 – Total precipitation<br/>
   15. reanalysis_max_air_temp_k – Maximum air temperature<br/>
   16. reanalysis_min_air_temp_k – Minimum air temperature<br/>
   17. reanalysis_avg_temp_k – Average air temperature<br/>
   18.   reanalysis_tdtr_k – Diurnal temperature range<br/>
   19. ndvi_se – Pixel southeast of city centroid<br/>
   20. ndvi_sw – Pixel southwest of city centroid<br/>
   21. ndvi_ne – Pixel northeast of city centroid<br/>
   22. ndvi_nw – Pixel northwest of city centroid<br/>

