# Web Development with Node and Express
### by Ethan Brown

## Chapter 1

## Chapter 2

## Chapter 3
- We use `app.get` to add routes. It takes two params: a path and function
    - the path defines the route
    - the function will get invoked when the route is matched
- instead of Node's `res.end` we use Express's `res.send`
- instead of Node's `writeHead` we use Express's `res.set` and `res.status`

- For 404 and 500 we use `app.use`
    - `use` is the method by which Express adds middleware
    - the order in which routes and middleware are added is important
