# Minimax Algorithm

The two players in a two person game are traditionally referred to as Max and Min
* Max represents the player who attempts to maximize the heuristic evaluation
* Min represents the player seeking to minimize it.

Players alternate moves, with Max genreally moving first

Assume that heuristic values have been assigned to each of the moves possible for any player in a given position.

Also assume that for any game, each position has only two possible moves.

**Always remember a good move for Max is bad for Min**
* Additionally, all values in a game tree are considered from Max's vantage point.
* The Min player always makes the move with the minimum value attached to it, because the Min player is trying to minimize the value that accrues to Max.



# Minimax with Alpha-Beta Pruning
* Alpha-beta is a search algorithm that seeks to decrease the number of nodes that are evaluated by the minimax algorithm in its search tree.
* Alpha-beta usually examines only about one-half as many nodes as minimax alone
* So basically once alpha-beta discovers that a move is bad, that path/move is abandoned and additional resources are not expended to discover how truly bad it is.
* This is similar to branch and bound search in which partial paths are abandoned when they are found to be suboptimal.
