# Playwright-TypeScript-TodoApp E2E Automation

---
### Test Cases

The app you’ll be testing is the example React todomvc app located here – https://todomvc.com/examples/react/#/ 

#### Scenario
As a user of the [React todomvc](https://todomvc.com/examples/react/#/) app, I want to be able to add, delete and mark todo items as complete

#### Test case #1 

`Given I am a user of todomvc`\
`When I create a new todo item`\
`Then it appears last on my todo list`
 
#### Test case #2

`Given I have created a todo item`\
`When I edit a todo item`\
`Then the todo item gets updated with the new changes` 

#### Test case #3

`Given I have created a todo item`\
`When I delete a todo item using the red X`\
`Then the todo item is removed from my todo list`
 
#### Test case #4

`Given I have created a todo item`\
`When I mark a todo item as completed`\
`Then it is marked with a green check mark`\
`And it is crossed off my todo list with a Strikethrough` 

#### Test case #5

`Given I have marked a todo item as complete`\
`When I view the Active list`\
`Then only Active (Not Completed) todo items are shown`
 
#### Test case #6

`Given I have marked a todo item as complete`\
`When I click “Clear Completed”`\
`Then the completed todo item is removed from my todo list`\
`And the todo item is moved to the Completed list` 
