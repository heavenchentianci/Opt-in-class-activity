Author 
Tianci tc3507
Jiayue Gao jg5022
The planned path begins at the Bunker, then proceeds to the Gas Station, Hospital, Pharmacy, and finally the Grocers1 store before returning to the Bunker. This route was generated using a shortest-path + Traveling Salesperson Problem (TSP) framework. We first modeled the town as a weighted road network, where each street’s distance served as the travel cost. By computing all-pairs shortest paths, we ensured that only the safest and most direct streets were used. Then we solved a small tsp with the key points, Gas Station, Hospital, Pharmacy, and Groceries. The approach guranteed every critical point is visited, and find the mimal distance.
