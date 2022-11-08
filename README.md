# Society-based-Cooperation

A population of agents exists in an environment in which the location of an agent is
unknown and irrelevant; the only possible event in this environment is for a pair of
agents chosen at random to play a game. The game is very simple: each agent carries
out one of two possible actions, ‘cooperate’ or ‘be selfish’. The game payoffs to both
agents are described by the following table:

[]!(/images/table.png)

Every agent is a member of exactly one society, and there are four societies with
different rules of conduct to choose from. Each agent’s action is fully determined by the
rules of the society it belongs to, and whether the other agent belongs to the same
society or not. However, after the payoff from each encounter is received (and added to
the total payoff from all previous encounters), each agent may decide to leave its
current society and join another in an attempt to maximise its future payoff.
The four societies and their rules of conduct are as follows. Members of the “Saints”
society cooperate with everyone. Members of the “Buddies” Society always cooperate
with each other, but never with anyone else. Members of the “Fight Club” never
cooperate with each other, but always cooperate with everyone else. Members of the
“Vandals” Society never cooperate with anyone.
When an agent is selected to play a game, it must follow the strategy prescribed by the
society it is a member of. Once both players have determined their move, the
appropriate payoffs are handed out as listed in Table 1. After each game played, each
player is shown the total wealth of the other player, the current society that other player
belongs to, and it is allowed to leave its current society and join another one. (An agent
must always remain a member of exactly one of the four societies.) Each agent’s
personal objective is to maximise its total payoff over the course of the whole
simulation, which consists of repeating the above game N times, where the agents do
not know that number in advance, and for each round of the game, the pair of
participating agents is chosen afresh.
