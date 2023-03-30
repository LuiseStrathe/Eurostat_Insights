# Eurostat_Insights

### The European Union provides data via the Eurostat database. This repository contains a collection of scripts to analyze the data.

</br>

Thisrpoe focuses on visualizing and analyzing data that is related to <b>FORESTS AND WOODLANDS</b> in the European Union. The data is provided by Eurostat and can be found <a href='https://ec.europa.eu/eurostat/web/forests/data/database'>here</a>.

</br>

More info on the tables, sources and classification codes can be found in [DATA_INFO.md](DATA_INFO.md).



</br>

## Publications
<b><a href='https://public.tableau.com/app/profile/luise7056/viz/TheEuropeanForests/Dashboard1'>European Forests Tableau Dashboard</a></b>



</br>

## Structure

The repository is structured as follows:

- DATA
    - raw
        contains the raw data from Eurostat
    - dataframes
        contains the dataframes created from the raw data
    - processed
        contains the processed data

- NOTEBOOKS
    contains the notebooks used to analyze the data
    - unpack_data
        create dataframes from the raw data
