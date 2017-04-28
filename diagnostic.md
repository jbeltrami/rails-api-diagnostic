# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
Access and manipulate data, before sending it back to front-end
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The Controller communicates with the Model to fetch data.
```

Which layer in the MVC pattern communicates with the model?

```md
The controller communicates with the Model
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Because so far we've developed single page applications, so there is no need for the Model to search for front-end data.
```

What does C.R.U.D stand for?

```md
Create
Read
Update
Destroy (Delete)
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
In the routes.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
POST data
GET single data (using an ID for example)
GET index
UPDATE (or PATCH) data
DESTROY (or DELETE) data
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
The CLIENT will send the GET request to the server.
The SERVER will find the correspondent ROUTE to the CONTROLLER.
The CONTROLLER will communicate the request to the MODEL.
The MODEL will do that task.
The MODEL will communicate back to the CONTROLLER with the response.
The CONTROLLER will send the response to the server.
The SERVER will send the response to be displayed to the CLIENT
```

What is the command to generate a new rails-api app?

```bash
rails new
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
db:drop
db:create
db:migrate
db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold post title:pet name:text age:integer
```
