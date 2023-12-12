# CLI Todo
App todo cli with **Golang saving to json file**

## Installation
```bash
git clone https://github.com/codepnw/cli-todo-app.git

cd cli-todo-app

## run
go run cmd/main.go

## build
go build -o todo cmd/main.go
```

##  Running
Data save to file **.todos.json**

```bash
## List all todos
./todo -list

## Add new todo
./todo -add example

## Change todo status
./todo -complete=<todo_id>

## Delete todo
./todo -del=<todo_id>

## sending from another program
echo "sending data from another program" | ./todo -add
```
