# Helm Charts

This repository contains packaged Helm charts provided by Prashanth Bodepu.   
The chart files is used for creating a sample helm charts


## Add Repository (stable)
`$ helm repo add todo-api https:/0xpb1.github.io/helmv1/todo-api/artifacthub/`   
`$ helm repo list`
`$ helm repo update`
`$ helm search repo -l todo-api`
`$ helm install <release_name> <helm_repo_name>/<chart_name> --version=1.0.0`

![image](https://github.com/0xPb1/helmv1/assets/82134963/1fe42e7f-09d5-4934-8707-fcb716ce4c40)

`$ helm install todo-api-release todo-api/todo-api`
