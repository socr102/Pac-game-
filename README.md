# Pacman Capture the Flag

You must read fully and carefully the assignment specification and instructions detailed in this file. You are NOT to modify this file in any way.


Note that the Pacman tournament has different rules as it is a game of two teams, where your Pacmans become ghosts in certain areas of the grid. Please read carefully the rules of the Pacman tournament. Understanding it well and designing a controller for it is part of the expectations for this project. Additional technical information on the contest project can be found in file [CONTEST.md](CONTEST.md). 


## 1. Your task

**Your task** is to develop an autonomous Defensive Pacman agent team to play the [Pacman Capture the Flag Contest](http://ai.berkeley.edu/contest.html) by suitably modifying file `myTeam.py` (and possibly some other auxiliary files you may implement). The code submitted should be internally commented at high standards and be error-free and _never crash_. 

The Solution for the Defensive agent should implement one of the methods below

1. Classical Planning (PDDL and calling a classical planner).
2. Value Iteration (Model-Based MDP).
3. Monte Carlo Tree Search or UCT (Model-Free MDP).
4. Reinforcement Learning – classical, approximate or deep Q-learning (Model-Free MDP).

You can always use hand coded decision trees to express behaviour specific to Pacman, but they won't count as a required technique. You are allowed to express domain knowledge, but remember that we are interested in "autonomy", and hence using techniques that generalise well. The 4 techniques mentioned above can cope with different rules much easier than any decision tree (if-else rules). If you decide to compute a policy, you can save it into a file and load it at the beginning of the game, as you have 15 seconds before every game to perform any pre-computation.

### Basic rules & guidelines

* Code **must run _error-free_ on Python 3.6/3.8**. 

* You are **not to change or affect (e.g., redirect) the standard output or error channels** (`sys.stdout` and `sys.stderr`) beyond just printing on standard output. If your file mentions any of them it will be breaking the "fair play" of the course (see below). These are used to report each game output and errors, and they should not be altered as you will be interfering negatively with the contest 

Additional technical details can be found in [CONTEST.md](CONTEST.md). 


