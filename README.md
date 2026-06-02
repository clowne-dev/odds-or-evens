# Even or Odd 🎲

Even or Odd game with a dynamic scoring and penalty system.

## How to play

- A number between 0 and 100 appears on the screen.

- Choose **even** or **odd** before revealing it.

- Correct: **+4 points**
- Incorrect: **-4.x points** (the penalty increases with each error)

## Penalty Rules

| Situation | What happens |
|---|---|
| Correct | Penalty reduced by `0.1 + (0.x)` |
| Incorrect | Penalty increased by `0.1` |
| Minimum penalty | Locked at **3.3 pts** |
| After locking at 3.3 | Penalty = `3.3 + 0.1 + (0.05 + 0.x)` per error |
| 6 consecutive correct answers | Loop error counter **resets** |

The game lasts **90 attempts**.

Game link: https://clowne-dev.github.io/odds-or-evens/
