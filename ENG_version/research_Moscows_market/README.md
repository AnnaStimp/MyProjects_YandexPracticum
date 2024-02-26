# Moscow market research

## Data

- ``name`` — name of the establishment;
- ``address`` — address of the establishment;
- ``category`` - category of the establishment, for example “cafe”, “pizzeria” or “coffee shop”;
- ``hours`` — information about days and hours of work;
- ``lat`` — latitude of the geographical point in which the establishment is located;
- ``lng`` — longitude of the geographical point in which the establishment is located;
- ``rating`` — rating of the establishment according to user ratings in Yandex Maps (the highest rating is 5.0);
- ``price`` - category of prices in the establishment, for example “average”, “below average”, “above average” and so on;
- ``avg_bill`` - a string that stores the average order cost as a range, for example:
     - “Average bill: 1000–1500 ₽”;
     - “Price of a cup of cappuccino: 130–220 ₽”;
     - “Price of a glass of beer: 400–600 ₽.”
- ``middle_avg_bill`` - a number with an estimate of the average bill, which is indicated only for values ​​from the avg_bill column starting with the substring “Average bill”:
     - If a row contains a price range of two values, the column will include the median of these two values.
     - If a line contains one number - a price without a range, then this number will be included in the column.
     - If there is no value or it does not start with the substring “Average score”, then nothing will be included in the column.
- ``middle_coffee_cup`` - a number with the price of one cup of cappuccino, which is specified only for values ​​from the avg_bill column starting with the substring “Price of one cup of cappuccino”:
     - If a row contains a price range of two values, the column will include the median of these two values.
     - If a line contains one number - a price without a range, then this number will be included in the column.
     - If there is no value or it does not begin with the substring “Price of one cup of cappuccino,” then nothing will be included in the column.
- ``chain`` - a number expressed as 0 or 1, which indicates whether the establishment is a network establishment (for small networks errors may occur):
     - 0 — the establishment is not a chain
     - 1 — the establishment is a chain establishment
- ``district`` - the administrative district in which the establishment is located, for example the Central Administrative District;
- ``seats`` — number of seats.

## Task

Investors from the "Shut Up and Take My Money" fund decided to try themselves in a new area and open a catering establishment in Moscow. Customers do not yet know what kind of place it will be and what the location, menu and prices will be. A dataset with Moscow catering establishments is available, compiled on the basis of data from the Yandex Maps and Yandex Business services for the summer of 2022. It is necessary to prepare a study of the Moscow market, find interesting features and present the results obtained.

## Libraries used
*pandas*, *matplotlib*, *numpy*, *folium*, *json*, *seaborn*