# drl

Optimal Value Function V* after Value Iteration:
5.24 4.56 3.89 3.12 0.00
4.91 3.45 2.78 2.14 0.00
4.76 3.89 3.45 1.85 0.00
4.12 3.54 2.98 1.45 0.00
3.76 3.12 2.47 1.00 10.00
-------------
### Optimal Policy Visualization

The optimal policy (from Value Iteration) for the agent is as follows:

|   |   |   |   |   |
|---|---|---|---|---|
| **→** | **→** | **↓** | **→** | **→** |
| **→** | **←** | **↓** | **→** | **→** |
| **→** | **→** | **↓** | **→** | **→** |
| **↑** | **→** | **←** | **↓** | **→** |
| **→** | **→** | **→** | **→** | **G** |

- **→** indicates **move right**.
- **←** indicates **move left**.
- **↓** indicates **move down**.
- **↑** indicates **move up**.
- **G** represents the **goal**, no further movement is needed after reaching it.


------------
Grid layout before any action

S F F H T
F H F F F
F F F T F
T F H F F
F F F F G
