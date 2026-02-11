# Project

> Weigth: 20%\
> Due: March 11

**Yahtzee** is a dice game where the objective is to score points by
rolling five dice to make certain combinations. Each round, players
choose one of the following categories to score their roll:

| Category        | Condition                    | Score           |
| --------------- | ---------------------------- | --------------- |
| Aces            | None                         | Sum of 1s       |
| Twos            | None                         | Sum of 2s       |
| Threes          | None                         | Sum of 3s       |
| Fours           | None                         | Sum of 4s       |
| Fives           | None                         | Sum of 5s       |
| Sixes           | None                         | Sum of 6s       |
| Three of a Kind | At least three dice the same | Sum of all dice |
| Four of a Kind  | At least four dice the same  | Sum of all dice |
| Full House      | Three of a Kind plus a pair  | 25              |
| Small Straight  | Sequence of four             | 30              |
| Large Straight  | Sequence of five             | 40              |
| Yahtzee         | Five dice the same           | 50              |
| Chance          | None                         | Sum of all dice |

Your task is to implement a function `score` that returns the score of a
given dice `roll` for a specified `category`. If the roll does not
satisfy the condition for the chosen category, the score is 0. For
example, given the roll `[1, 1, 3, 5, 6]` and the category
`"Three of a Kind"`, the score is 0 because the roll does not contain
three dice of the same value. Similarly, if the given category name does
not match any of the categories listed above, the score is 0.

## Starter files and submission

To access the starter files, first [accept the assignment][Classroom],
then download the repository (Code → Download ZIP). To submit your
assignment, upload only the `index.ts` on GitHub. Do not rename it, zip
it, or place it inside a folder.

[Classroom]: https://classroom.github.com/a/bP8soN_f

## Assessment criteria

- Program design [5]
  - requirements are met
  - tests pass
  - program flow is decomposed into manageable, logical pieces
  - data structures are appropriate
  - common code is unified, not duplicated
  - appropriate algorithms are used, and coded cleanly
  - no global variables
  - code is lint-free (run `bun lint`)

- Readability [5]
  - constants are used instead of hard-coded values
  - complex or meaningful expressions are named
  - naming is consistent and descriptive
  - inline comments are used only to explain reasoning
  - type annotations are correct (run `bun typecheck`)
  - functions are well-documented
  - code is formatted (run `bun fmt`)
