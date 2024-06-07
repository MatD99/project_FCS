# project_FCS_2324

In questo file sono presenti il codice python del progetto di foundations of computer science e le cartelle contenenti i vari file csv rigurdanti le informazioni dei viaggi dei bus e le loro caratteristiche,sulle quali vengono eseguite i vari task del progetto (query). 

QUERY DA ESEGUIRE
1. Extract all trips with busRoute 83
2. Extract all trips where busRoute is not a number
3. For each (busNumber, busRoute) pair, determine the number of trips
4. For each trip, compute the ratio between the energy consumption and the average number of passengers
5. For each station (itcs_stopName), determine the average number of passengers.
6. For each station, determine the buses that have stopped there at least once.
7. For each station, determine the buses that have stopped there at least ten times.
9. For each (route, bus) pair, compute the ratio between the overall energy consumption and the overall driven distance.
10. Starting from the results of the previous point, for each route compute the buses with max and min energy ratio, and save the difference between these ratios in a dataframe.
11. Find the bus maximizing the difference computed in the previous point.
12. Extract the rows of the details such that the gnss_altitude differs from the value in the preceding row. Store also the difference in the variable altitude_variation.
13. For each details dataset, compute the sum of the absolute value (i.e. the sign is not considered) of altitude_variation.
14. For each month of the year, compute the average ambient temperature
15. For each bus compute the total time when the halt brake is active and the total time when the park brake is active. Compute also the ratio between those two times.
16. For each pair of stops that are consecutive in at least a trip, compute the average speed achieved when going from the first to the second stop.
