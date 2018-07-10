# US_Household_Income

This repository has stored procedures and SSRS reports.

1. Stored procedure 'sp_getIncomeByLocation' takes parameters state_name, state_ab, county, city or zipcode from front-end input and search for household income data (median, mean, stdev and number of households) in specified locations.

2. Stored procedure 'sp_getLocation' takes min and max median household income or min and max of number of households from front-end user input. It then search location and geographical data with median income or household number within user defined range.

3. Folder 'SSRS_Reports' has demo reports for household income in WI and US which are created using Microsoft SSRS.
