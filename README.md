# Computing best pokemon types

here we try to find what is the strongest pokemon type, looking exclusively at the type matchup chart.

we define strong using three principles:

1. a strong type has a high offensive score
2. a strong type has a low weakness (defensive) score
3. a strong type has good scores against other strong types

to follow principle 3 we use an iterative process, where we: score all types in one iteration; assign weights based on those scores; re-score them based on these weights in the next iteration.

typings are given balanced, offensive and defensive rankings for gen 6 onwards (post the introduction of the fairy type) and gen 5.

finally, we also rank all dual typings.