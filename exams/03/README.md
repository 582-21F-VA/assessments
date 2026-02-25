# Exam 3

> Weight: 10%\
> Due: March 2

Your repository includes a `index.ts` file with an array of CSS colors.
It also includes an HTML document named `index.html`, which contains an
empty `<ul>` (unordered list) element.

Using JavaScript, dynamically populate the list with the colors from the
array. Each list item should be displayed in the color that matches its
name. For example, the text of the brown item should be brown, the red
item should be red, and so on.

You are not allowed to modify the `index.html` file.

## Starter files and submission

To access the starter files, first [accept the assignment][Classroom],
then download the repository (Code → Download ZIP). To submit your
assignment, upload only the `index.ts` on GitHub. Do not rename it, zip
it, or place it inside a folder.

[Classroom]: https://classroom.github.com/a/N6jG2gzo

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
