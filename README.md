# todomvc-sagas-crud-example

This is an example of a todomvc crud application using [redux](https://github.com/reactjs/redux) and [redux-sagas](https://github.com/yelouafi/redux-saga)

It makes calls to the express server endpoints for the typical use cases: ```[ ADD_TODO_REQUESTED, /add-todo ]```, ```[ DELETE_TODO_REQUESTED, /delete-todo ]```, ```[ COMPLETE_TODO_REQUESTED, /complete-todo ]``` etc.

It is using an in-memory database to store the information using [nedb](https://github.com/louischatriot/nedb)

## Install and Run

```bash
$ npm install && npm run start
```

## LICENSE

MIT