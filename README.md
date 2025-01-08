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
### Optimal Value Function V* after Value Iteration

The optimal value function (V*) represents the expected cumulative reward for each state after applying value iteration. Here's the value function for each state on the 5x5 grid:

| **5.24** | **4.56** | **3.89** | **3.12** | **0.00** |
|----------|----------|----------|----------|----------|
| **4.91** | **3.45** | **2.78** | **2.14** | **0.00** |
| **4.76** | **3.89** | **3.45** | **1.85** | **0.00** |
| **4.12** | **3.54** | **2.98** | **1.45** | **0.00** |
| **3.76** | **3.12** | **2.47** | **1.00** | **10.00** |

- The values represent the **expected cumulative reward** starting from each state.
- **0.00** corresponds to states that are **goal** or **unsafe** (like falling into holes).
- **10.00** is the **maximum value** at the goal state (reaching the goal gives the agent the highest reward).

