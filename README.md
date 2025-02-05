# Tasks - schedule commands to run periodically
running `tasks --help`:
``` 
tasks - schedule commands to run periodically
  install                          - install script in $INSTALLATION_DIR
  list                             - list all available tasks
  add <command> <hour> <minute>    - schedule a command to run daily at <hour> and <minute>
  remove <number>                  - remove task
  kill                             - kill all running instances of $0
  help                             - show this help message
  start                            - start tasks runner process
```
# Installation
```
git clone github.com/hamza-algohary/tasks
cd tasks
./tasks install
```
Then schedule "tasks start" to run at startup