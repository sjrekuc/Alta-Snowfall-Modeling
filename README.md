# Alta Snowfall Analysis

============================

Skiers love skiing in good snow conditions with fresh snowfall, but most skiers (and certainly many of the big spenders in skiing) have to book their ski trips far in advance of a reasonable weather forecast. However, some areas may have snowfall patterns that can be studied to determine if some weeks or months of the ski season receive more snowfall than other times. Even the slight chance that resort will fair better would provide a skier with valuable knowledge in booking a vacation. 

## Project Organization

----------- <br>
- LICENSE <br>
- README.md     <- Top-Level Readme for anyone interested in this project <br>
- DATA <br>
  - Raw       <- Original CSV Data from NOAA <br>
    - alta_ski_v2.csv   <- Original CSV Data from NOAA station at the base of Alta (UDOT Station) <br>
    - PDO_NOAA.csv.txt  <- Original CSV Data from NOAA for the Pacific Decadal Oscillation (PDO) <br>
    - AMO_raw.csv       <- Original CSV Data from NOAA for the Atlantic Multi-Decadal Oscillation (AMO) <br>
  - Interim       <- Intermediate data that has been cleaned, combined, and transformed <br>
    - alta_snow_clean3.pkl   <- pickled (python binary) dataframe of combined and cleaned snowfall, temp, PDO, AMO data; between data wrangling + EDA <br>
    - alta_snow_clean3.csv   <- CSV dataframe of combined and cleaned snowfall, temp, PDO, AMO data <br>
    - alta_snow_eda.pkl      <- pickled (python binary) dataframe with some additional features; between EDA 1 + 2 <br>
    - alta_snow_eda.csv      <- csv dataframe with some additional features; between EDA 1 + 2 <br>
    - win_snow_eda.pkl       <- pickled (python binary) dataframe that is just focused on winter; between EDA 1 + 2 <br>
    - win_snow_eda.csv       <- csv dataframe that is just focused on winter; between EDA 1 + 2 <br>
    - X14_snow_pp.pkl        <- pickled dataframe that is summarized by 14-day snowfall; between EDA 2 + modeling <br>
    - X14_snow_pp.csv        <- csv dataframe that is summarized by 14-day snowfall; between EDA 2 + modeling <br>
    - X30_snow_pp.pkl        <- pickled dataframe that is summarized by 30-day snowfall; between EDA 2 + modeling <br>
    - X30_snow_pp.csv        <- pickled dataframe that is summarized by 30-day snowfall; between EDA 2 + modeling <br>
    - unused    <- folder containing interim data that went unused <br>           
  - Processed    <- Final Data Set used in modeling <br>
    - X7_snow_pp.pkl         <- pickled dataframe that is summarized by 7-day snowfall; between EDA 2 + modeling <br>
    - X7_snow_pp.csv         <- csv dataframe that is summarized by 7-day snowfall; between EDA 2 + modeling <br>

- NOTEBOOKS <- Named in order of data processing <br>
  - 1.0 - Capstone1_Data_Wrangling.ipynb <- Load the data, clean the data, and combine into 1 dataframe <br>
  - 2.1 - Capstone1_Alta_EDA.ipynb <- Exploratory Data Analysis of the data; part 1 of 2 <br>
  - 2.1 - Capstone1_Alta_EDA_2_pre-processing.ipynb <- Exploratory Data Analysis of the data; part 2 of 2 and preprocessing <br>
  - 3.0 - Capstone1_Alta_Modeling.ipynb <- Modeling of the data in time series with regression and RF <br>
  - extra <- notebooks with some code that were not used in the end <br>
  
- REPORTS <- Reports detailing the entire data science process for this project <br> 
  - Final_Rep_Alta_Snow.pdf <- Report detailing the data science process for this project <br>
  - Pres_Alta_Snow.pdf <- Presentation slides outlining the data science process for this project <br>

├── LICENSE <br>
        └── alta_ski_v2.csv   
