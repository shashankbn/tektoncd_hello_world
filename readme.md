# Installation on mac

brew tap tektoncd/tools
brew install tektoncd-cli

# Running examples

## Create cluster
k apply -f .

## create task
tkn task describe echo-hello-world

## create taskrun and check logs
tkn taskrun describe echo-hello-world-task-run
tkn taskrun logs echo-hello-world-task-run

ref:
https://github.com/tektoncd/pipeline/blob/master/docs/tutorial.md
