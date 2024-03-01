# BASIC TODO CLI MADE USING GOLANG
<p>
  Simple golang todo cli uses simpletable package to view the table and assign the colors.
  Operations like add task, delete task , mark as completed and list the tasks can be performed.
</p>

<h1> To set up in local </h1>

### Clone the package
    git clone https://github.com/utsab818/Todo-cli-golang.git

### Install the package
    go get -u github.com/alexeyco/simpletable 

### Build the project
    go build ./cmd/todo

### Add the task
    ./todo -add "<your task>"

### list the tasks
    ./todo -list
  ![image](https://github.com/utsab818/Todo-cli-golang/assets/66249507/413a364f-4c07-4524-8a61-f5b6f7bb8cc3)

### make the task as completed
    ./todo complete=<index of task>

### delete the task
    ./todo del=<index of task>
