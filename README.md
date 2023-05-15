# NYTimes Mini Crossword Time Series Forecasting
Fun data exploration into my personal NYTimes mini crossword times -- by no means is this analysis meant to be super rigorous! 

Main interesting takeaways I got:
* The distribution of the times actually looks fairly symmetric/normal after a log transformation. It's just skewed slightly to the right.
* In the absence of exogenous variables, such as features about the puzzles themselves, the main signal comes from the (known) weekly periodicity on Saturdays, when the puzzle is larger. The rest of the variance really does look like noise.

