# Installation

>brew tap tektoncd/tools

>brew install tektoncd-cli

# Running examples

## Create tekton tasks
> k apply -f .

## Check task
> tkn task describe echo-hello-world

## Check taskrun
> tkn taskrun describe echo-hello-world-task-run

## Check taskrun logs
> tkn taskrun logs echo-hello-world-task-run

ref:
https://github.com/tektoncd/pipeline/blob/master/docs/tutorial.md
