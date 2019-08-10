# Did Bugha just get lucky? Fortnite Monte Carlo Simulation
Kyle "Bugha" Giersdorf won the 2019 Fortnite World Cup with a 26 point margin over Psalm, the runner up. Did Bugha just get lucky, or is he more talented than the rest of the field? I'll use null hypothesis testing to answer this question.

# Hypothesis: Bugha is more talented than the rest of the field
# Null Hypothesis: Everyone is average, and results come from luck and random chance, not skill

The Fortnite World Cup is a battle royale tournament involving 100 players. In the solo event, players compete to get the most points. There are two ways to get points: eliminating opponents and placing (surviving the longest). A full explanation of the points system can be found here: https://www.dailyesports.gg/fortnite-world-cup-2019-scoring-point-system/

Using a Monte Carlo simulation, I'll simulate the Fortnite World Cup under the null hypothesis: every elimination goes to a random player. The random players who are left in the endgame get the placing points. A p-value is a measure of how likely a given event will occur given null hypothesis (random) testing conditions. I sought two p-values: the first for Bugha's 26 point margin over second place, and the second for Bugha's 27 point margin over third place. After a Monte Carlo simulation with 10000 iterations, I got 0.0011 for the first p-value, and 0.0019 for the second p-value. In other words, given random chance, there's a 0.11% chance anyone in the field would have achieved a 26 point margin over second place, and a 0.19% chance anyone would have achieved his 27 point margin over second place.
