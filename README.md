# CATE22-adpatative_model_brasil

This repository presents the data analysis done for the paper "Thermal comfort provision in naturally ventilated buildings:  a comparison between Brazil and North American standards". The paper will be presented at the [CATEE 22](https://comfortattheextremes.com/september-about/) conference.

We evaluated the temperature behavior for the eight bioclimatic zones in Brazil. Our goal was to determine if the temperatures were inside the applicable temperatures for the [ASHRAE 55](https://www.ashrae.org/technical-resources/bookstore/standard-55-thermal-environmental-conditions-for-human-occupancy) adaptative model.

We also computed the 80% acceptability temperature limits, given by:

$$upper_{80} = 0.31*\overline{t_{pma(out)}} + 21.3$$

$$lower_{80} = 0.31*\overline{t_{pma(out)}} + 14.3$$

where $\overline{t_{pma(out)}}$ is the running mean of the outdoor temperature.

We used a period of 7 days to compute the running mean and the function from the [pythermalcomfort library](https://pypi.org/project/pythermalcomfort/).

The data used was extracted from the [INMET database](https://bdmep.inmet.gov.br/). We used the period between 2019 and 2021 for all the stations available, and divided the data between the [8 bioclimatic zones](https://www.abntcatalogo.com.br/norma.aspx?Q=aXVWUnIvNmh2TStycVVzWFlvQTlyb0hhaVo3NDBFRk8=).

The figure presents the brazilian bioclimatic zones (adpated from the ABNT NBR 15.220) and the location of the weather stations: 

<img src="https://github.com/juliaplazari/CATE22-adpatative_model_brasil/blob/main/bioclimatic_zones_and_weather_stations.png" width="300" />

For more information about this project, you can email: j200298@dac.unicamp.br or juliana.oliveira@estudante.ufscar.br
