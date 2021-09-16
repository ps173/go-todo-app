# Purpose

Just a basic todo app for command line

# CLI Demo
[![asciicast](https://asciinema.org/a/KNjqSJItb4ES08xgFbVfKw6MP.svg)](https://asciinema.org/a/KNjqSJItb4ES08xgFbVfKw6MP)

# What Does it do

It is basic todo list for command line.

```bash
# sample commmands

$ todo --ls # lists all todos
 1. Create log file - [id]
 2. Nextjs Vimgore frontend - [id]

$ todo -del 1 # deletes the id
Deleted todo of id 1

$ todo -add something # creates a new todo
Added a todo of id 1

$ todo -da # deletes all the todos
Deleted all the todos

$ todo -ud 1 false # sets the first todo as done
Updated todo with id 1 as false
```

# building

You need golang installed on your system. Check [their official site](https://golang.org/dl/).
After installing golang. Clone the repo to local system.
```
$ git clone https://github.com/ps173/go-todo-app.git
```
After Cloning.Do `cd go-todo-app` and then run 
```
$ go build .
```

# More Soon..
