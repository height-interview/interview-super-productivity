# Interview

## Install

```
# Make sure to use node@16
brew install node@16
# or
npm install -g n
n 16

# Install super-productivity
cd super-productivity
npm install -g @angular/cli
npm install

# Run the server
ng serve
open "http://localhost:4200"

```

## Exercise 1: bug fix

### Expected Behavior

When the task description is cleared, losing the task description textarea focus should persist the empty content to the database.

### Current Behavior

The empty task description is not persisted.

### Steps to Reproduce

Given a task with a written task description:

1. Make sure the task has a description different than the description template.
2. Focus the task description textarea, clear all the content.
3. Lost task description textarea focus.
4. Close the task additional infos panel.
5. Re-open the task additional infos panel.
6. The task description is not cleared.

## Exercise 2: add feature

When creating a task in a project, the task is added to the top of the list by default.

1. The task should be added to the bottom of the list by default.
2. Add a parameter that can be used to control if the task is added at the top or the bottom.
3. Add a button in order to control if the task is added at the top or the bottom.
