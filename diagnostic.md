# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
// A backend exists to respond to a client's requests and to provide information .
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// The model is the MVC portion which provides responses to data requests.
```

Which layer in the MVC pattern communicates with the model?

```bash
// The view layer is responsible for sending data held in the model by the controller in response to a request.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// your response here
```

What does C.R.U.D stand for?

```bash
// CREATE, READ, UPDATE, DESTROY
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// CRUD actions are found in the controller
```

List at least 5 standard actions that C.R.U.D corresponds to?

```bash
// your response here
```

A user action fires a `GET` request for `/persons/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
// 1) user clicks a button to begin the response
// 2) client sends the 'GET' to specified host looking for the information in `/persons/1`
// 3) Server sends 'READ' to the controller for the data in `/persons/1`
// 4) Controller sends `SELECT` for the data to the model
// 5) Model acquires the data in `/persons/1` and sends back to the Controller
```

What is the command to generate a new rails-api app?

```bash
// bundle exec rails-api g scaffold
```

What is the command to start an instance of a rails server?

```bash
// bundle exec rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
// 1) ??? (bundle exec rake db:drop ?)
// 2) bundle exec rake db:create
// 3) bundle exec rake db:migrat
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// bundle exec rails-api g scaffold user name:string age:string

```
