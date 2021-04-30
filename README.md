# Tekton GitHub Actions Demo

![Build](https://github.com/jerop/test-tkn/actions/workflows/cd.yaml/badge.svg)

An example usage of [`tkn` GitHub Action][tkn-action] to lint, test, build and run a [Hello World Go app](hello.go) 
using [Tekton][tekton]. 

[`tkn` GitHub Action][tkn-action] configures [`tkn`][tkn] in the environment for managing 
[Tekton](https://tekton.dev/) resources in GitHub Actions.

[Tekton][tekton] is a powerful yet flexible Kubernetes-native open-source framework for creating continuous integration 
and delivery (CI/CD) systems. It lets users build, test, and deploy across multiple cloud providers or on-premises 
systems by abstracting away the underlying implementation details.

[tkn-action]: https://github.com/jerop/tkn
[actions]: https://help.github.com/en/categories/automating-your-workflow-with-github-actions
[tekton]: https://tekton.dev/
[tkn]: https://github.com/tektoncd/cli