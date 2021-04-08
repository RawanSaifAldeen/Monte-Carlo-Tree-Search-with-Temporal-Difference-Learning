# Monte-Carlo-Tree-Search-with-Temporal-Difference-Learning
A research project done at the end of the distributed AI module (MSc. Data Science @ Lancaster University)

Abstract:
TD-UCT is a variation of the on-policy planning
algorithm MCTS which combines UCB1 and TD learning when
performing the tree policy of the tree search, this is done as an
attempt to improve the performance of MCTS. TD-UCT uses a
linear combination of the estimated Q-value of a state-action pair
obtained using TD learning and the estimated Q-value defined as
the mean backed-up reward, the linear combination is controlled
using a variable wtd. In this paper, this method was investigated
for the optimal value of wtd when applied to gym’s Frozen Lake
game. It was found that wtd = 1 gives the best performance
where all episodes were won when using 600 simulations per move
and above, while the average number of steps before winning an
episode was found to reach 6.26+-0.027 steps at 1000 simulations
per move, where 6 is the minimum number of steps to reach the
goal.
