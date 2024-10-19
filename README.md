# Ultra-Marathon-UM-Race-Analysis
The project looks at Ultra-Marathon records for 50km and 50mi events in the USA during 2020. It starts by loading a dataset and making a copy for safety. Initial checks reveal the dataset's structure, including its size and data types.

Next, the data is cleaned by filtering for only the 50km and 50mi events held in 2020. The project ensures it includes only USA events by checking the "Event name." Irrelevant columns are removed, and a new column for athlete age is added by subtracting the year of birth from 2020. Any missing values are dealt with, and duplicates are checked and removed as needed.

The analysis addresses several questions, such as finding details about a specific event and athlete. Histograms show the count of race lengths and can be colored by athlete gender for further insight. The project examines athlete performance by plotting average speeds and comparing speeds between male and female runners.

Age groups are analyzed to see which performed well and which did not in the 50mi race. The project looks at the average speed of different age groups and identifies trends based on participation numbers.

Finally, it analyzes race performance by season. The month of each race is extracted, and races are categorized into spring, summer, fall, or winter. The average speeds are calculated for each season, giving insights into how athletes performed throughout the year. This project provides a clear view of athlete performance across different events and demographics in the 2020 Ultra-Marathon races.
