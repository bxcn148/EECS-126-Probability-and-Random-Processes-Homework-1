Download link :https://programming.engineering/product/eecs-126-probability-and-random-processes-homework-1/


# EECS-126-Probability-and-Random-Processes-Homework-1
EECS 126: Probability and Random Processes Homework 1
. Coin Flipping & Symmetry

Alice and Bob have 2n + 1 fair coins (where n 1), each coin with probability of heads equal to 1=2. Bob tosses n+ 1 coins, while Alice tosses the remaining n coins. Assuming independent coin tosses, show that the probability that, after all coins have been tossed, Bob will have gotten more heads than Alice is 1=2.

Hint: Consider the event A = fmore heads in the rst n + 1 tosses than the last n tossesg.

2. Passengers on a Plane

There are N passengers in a plane with N assigned seats (N is a positive integer), but after boarding, the passengers take the seats randomly. Assuming all seating arrangements are equally likely, what is the probability that no passenger is in their assigned seat? Compute the probability when N ! 1.

Hint: Use the inclusion-exclusion principle and the power series ex = P1 xj =j!.

j=0

3. Expanding the NBA

The NBA is looking to expand to another city. In order to decide which city will receive a new team, the commissioner interviews potential owners from each of the N potential cities (N is a positive integer), one at a time. Unfortunately, the owners would like to know immediately after the interview whether their city will receive the team or not. The commissioner decides to use the following strategy: she will interview the rst m owners and reject all of them (m 2 f1; : : : ; Ng). After the mth owner is interviewed, she will pick the rst city that is better than all previous cities. The cities are interviewed in a uniformly random order. What is the probability that the best city is selected? Assume that the commissioner has an objective method of scoring each city and that each city receives a unique score.

You should arrive at an exact answer for the probability in terms of a summation. Approximate

your answer using

in=1 i 1 ln n and nd the optimal value of m that maximizes the

best city is selected. You can also say ln(n 1)

ln n.

probability that theP

Hint: Consider the events Bi = fi-th city is the bestg and A = fbest city is choseng.

4. Random Walk on a Circle

Suppose we have n points labeled f1; 2; : : : ; ng around a circle. An ant starts at point 1, and at each second has an equal probability of moving clockwise or counterclockwise to an adjacent point. For each point k 2 f2; 3; : : : ; ng, nd the probability that the rst time the ant lands at k, it has visited all other points already.

5. Superhero Basketball

Superman and Captain America are playing a game of basketball. At the end of the game, Captain America scored n points and Superman scored m points, where n > m are positive integers. Supposing that each basket counts for exactly one point, what is the probability that


after the start of the game (when they are initially tied), Captain America was always strictly ahead of Superman? (Assume that all sequences of baskets which result in the nal score of n baskets for Captain America and m baskets for Superman are equally likely.)

Hint: Think about symmetry. First, try to gure out which is more likely: there was a tie and Superman scored the rst point, or there was a tie and Captain America scored the rst point?
