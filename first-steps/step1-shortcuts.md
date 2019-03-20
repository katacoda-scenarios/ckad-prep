Kubectl has support for auto-completion allowing you to discover the available options. This is applied with `source <(kubectl completion bash)`{{execute}}

Aliases also help reduce typing required and supports aliases as `alias k="kubectl"; source <(kubectl completion bash | sed 's/kubectl/k/g')`{{execute}}
