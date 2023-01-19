# [TODO application](https://viknikolaiev.github.io/todo_app/)

![alt text](https://vik-nikolaiev.s3.eu-central-1.amazonaws.com/todo-preview.png "Bose Landing Page")

A TODO app touches on all the important parts of building any data-driven app, including the Create, Read, Update and Delete (CRUD) operations. This app has built with one of the most popular Javascript frameworks - React.

## Application features

### Authorization
Authorization on the server by e-mail.

### Adding a todo
Adding a todo with a title

### Changing the status of a todo
Change todo status: active or completed.
Bulk todo`s status change is possible.

### Renaming a todo
Todo name change.

### Filtering todos
Filter by todo status: All, Active, Completed.

### Deleting todos
Deleting a single Todo or bulk deleting all Completed Todos.

## Links:

+ [Live Preview](https://viknikolaiev.github.io/todo_app/)

## Technology stack

Used technologies:

- HTML5
- SASS (CSS Preprocessor)
- BEM methodology
- Bulma, Fontawesome
- Javascript
- React
- AJAX (FETCH)


## Quick start

Quick start options:

- [Download from Github](https://github.com/VikNikolaiev/todo_app.git).
- Clone the repo: `git clone https://github.com/VikNikolaiev/todo_app.git`.


### What's included

Within the download you'll find the following working directories and files:

```
src/
│   App.tsx
│   index.tsx
│   react-app-env.d.ts
├───api
│       todos.ts
│       users.ts
├───components
│   ├───Auth
│   │       AuthContext.tsx
│   │       AuthForm.tsx
│   ├───BottomBar
│   │       BottomBar.tsx
│   │       index.tsx
│   ├───Notification
│   │       index.tsx
│   │       Notification.tsx
│   ├───TodoAddForm
│   │       index.tsx
│   │       TodoAddForm.tsx
│   ├───TodoItem
│   │       index.tsx
│   │       TodoItem.tsx
│   ├───TodoList
│   │       index.tsx
│   │       TodoList.tsx
│   ├───Todos
│   │       index.tsx
│   │       Todos.tsx
│   └───TodosStatusToggler
│           index.tsx
│           TodosStatusToggler.tsx
├───styles
│       filter.scss
│       index.scss
│       todo.scss
│       todoapp.scss
├───types
│       ErrorType.tsx
│       FilterType.ts
│       Todo.ts
│       TodoModifier.ts
│       User.ts
└───utils
        fetchClient.ts
```
