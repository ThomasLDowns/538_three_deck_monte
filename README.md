# 538_three_deck_monte
Jupyter Python notebook to simulate 538 Riddler problem.

https://fivethirtyeight.com/features/can-you-escape-a-maze-without-walls/

First, defined the three decks as arrays of numbers. Wrote a function that takes in two of those deck arrays and a number of runs in order to do a Monte-Carlo simulation of how the games would play out. This is done by shuffling each deck array, and then going card-by-card to see who won each flip. This process is continued until either the first deck or the second deck has won 5 total times. Upon this happening, the respective deck records a win, and then the process is continued for "num_runs" iterations. 

The results of this simulation show that there is definitely a best/worst deck to pick, and that the "winning" deck should be expected to win ~ 70% of the time. 
