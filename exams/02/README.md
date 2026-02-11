# Exam 2

> Weight: 10%\
> Due: February 16

For this assignment, your task is to implement a function named
`createInventory` that summarizes a list of items into a `Map` where
items are paired with their respective quantity.

For example:

```ts
expect(createInventory(["wood", "wood", "coal"]))
    .toEqual(new Map([["wood", 2], ["coal", 1]]));
```

Here, `"wood"` has a quantity of `2` because it appears twice in the
given list, while `"coal"` has a quantity of `1` because it appears only
once.

## Starter files and submission

To access the starter files, first [accept the assignment][Classroom],
then download the repository (Code → Download ZIP). To submit your
assignment, upload only the `index.ts` on GitHub. Do not rename it, zip
it, or place it inside a folder.

[Classroom]: https://classroom.github.com/a/_7AxiP7D

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
  - code is formatted (run `bun fmt`)
