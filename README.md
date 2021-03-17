# Property Value and Predictive Model Building

## Project Description
This project requires analyzing and building some models to assess and predict the assessed value of properties in the greater Boston area. After comparing, choose the model with best performance and decide which variables are the top influencers of property value.

## Tools and Learning Methods
Decision Tree, Gradient Boosting (XGBoost), k-fold cross validation

## Raw Data
Training set of 10k+ records
Test set of 4k+ records

## Data Dictionary 1

| Name | Description |
| --- | --- |
| PID | Unique parcel number |
| ZIPCODE | Zip for the parcel |
| OWN_OCC | One-character code indicating if owner received residential exemption as an owner-occupied property |
| AV_TOTAL | Assessed value for property |
| LAND_SF | Parcel's land area in square feet |
| YR_BUILT | Year property was built |
| YR_REMOD | Year property was last remodeled |
| LIVING_AREA | Living area square footage of the property |
| NUM_FLOORS | Number of levels in the structure located on the parcel |
| STRUCTURE_CLASS | Structural classification of commercial building |
| R_BLDG_STYL | Residential buiilding style |
| R_ROOF_TYP | Structure roof type |
| R_EXT_FIN | Structure exterior finish |
| R_TOTAL_RMS |	Total number of rooms in the structure |
| R_BDRMS	| Total number of bedrooms in the structure |
| R_FULL_BTH | Total number of full baths in the structure |
| R_HALF_BTH | Total number of half baths in the structure |
| R_BTH_STYLE | Residential bath style |
| R_KITCH |	Total number of kitchens in the structure |
| R_KITCH_STYLE |	Residential kitchen style |
| R_HEAT_TYP | Structure heat type |
| R_AC | Indicates if the structure has air conditioning (A/C) |
| R_FPLACE | Total number of fireplaces in the structure |
| R_EXT_CND | Residential exterior condition |
| R_OVRALL_CND | Residential overall condition |
| R_INT_CND |	Residential interior condition |
| R_INT_FIN |	Residential interior finish |
| R_VIEW | Residential view |

## Data Dictionary 2
| Name | Description |
| --- | --- |
| ZIP |	ZIP CODE |
| POPULATION | Population of people in the ZIP code  |
| POP_DENSITY |	People per square mile  |
| MEDIAN_INCOME |	Median Income of the residence of that zip code   |
| City_State | City Name and State  |
