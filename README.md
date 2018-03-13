# kubectl_autocomplete

Put this file to /etc/bash_completion.d/kubectl

then after relogin, or executing command . /etc/bash_completion.d/kubectl

you should be able to use autocompletion for kubectl

autocomplete features:
- namespaces
- all default arguments
- pods (current ns pods)
- pv (all pv in cluster)
- pvc (current ns pvc)
- logs (current ns pods)
- -ti (current ns pods)
- configmaps (current ns configmaps)
- deployments (current ns deployments)
- jobs
- -o (output yaml|wide)
