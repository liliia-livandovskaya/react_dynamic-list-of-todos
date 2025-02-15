# React dynamic list of TODOs

You are given the markup for the `App`, `TodosList`, `TodoFilter`, `TodoModal`
and `Loader` components. Load data from [the API](https://mate-academy.github.io/fe-students-api/) and show it using the given components.

1. Load [the todos](https://mate.academy/students-api/todos) when the `App` is
loaded and show them using `TodoList`;
1. Show the `Loader` when waiting any data from the server;
1. Use the `wait` function given in the `api.ts` to check if the `Loader`
works as expected;
1. When the `Show` button is clicked open the `TodoModal` with a selected `todo`;
1. Don't forget to load [user details](https://mate.academy/students-api/users/1) (replace `1` with the actual `userId`);
1. `x` button should close the modal;
1. The `select` should filter todos by the `completed` status: `all`, `completed` and `active`(not completed) todos;
1. Use the `input` in the `TodoFilter` to filter the `todos` by `title`;
    - show the `x` button when the `query` is entered;
    - the `x` button should clear the `query` and reset the todos;

## (*) Advanced tasks (optional)

1. Add `debounce` to the search input;
1. Add `Randomize` button to the `App` to show the `todos` in a random order.

## Instructions

- Implement a solution following the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline).
- Use the [React TypeScript cheat sheet](https://mate-academy.github.io/fe-program/js/extra/react-typescript).
- Open one more terminal and run tests with `npm test` to ensure your solution is correct.
- Replace `<your_account>` with your Github username in the [DEMO LINK](https://<your_account>.github.io/react_dynamic-list-of-todos/) and add it to the PR description.