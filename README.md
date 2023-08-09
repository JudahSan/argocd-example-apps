# ArgoCD Example Apps

**Introduction to Argo CD Repository**

Welcome to the Argo CD Example Apps repository! This repository, originally forked from [https://github.com/mabusaa/argocd-example-apps](https://github.com/mabusaa/argocd-example-apps), serves as a valuable resource to explore and learn about the capabilities of Argo CD – a powerful GitOps continuous delivery tool.

Argo CD simplifies the deployment and management of applications in Kubernetes clusters through the GitOps methodology. By defining your desired application state declaratively in Git repositories, Argo CD ensures that your live environment consistently matches the defined state. This approach enhances collaboration, reduces errors, and empowers efficient development and operations practices.

Inside this repository, you will find:

- **Sample Applications**: A curated collection of sample applications that showcase various deployment scenarios, strategies, and configurations.

- **Configuration Files**: YAML files and configurations demonstrating how to define, manage, and version your applications using Argo CD.

- **Documentation**: Resources, guides, and tips to help you get started with Argo CD and successfully implement GitOps practices.

Whether you are a seasoned Kubernetes professional or just beginning your journey into the world of container orchestration, this repository provides a hands-on experience to understand and harness the potential of Argo CD. Explore the sample applications, experiment with the configurations, and embark on a journey toward seamless, automated application deployment.

Feel free to delve into the contents of this repository, ask questions, contribute, and collaborate with fellow enthusiasts. The power of Argo CD and GitOps awaits you!

This repository contains example applications for demoing ArgoCD functionality. Feel free
to register this repository to your ArgoCD instance, or fork this repo and push your own commits
to explore ArgoCD and GitOps!

| Application | Description |
|-------------|-------------|
| [guestbook](guestbook/) | A hello word guestbook app as plain YAML |
| [ksonnet-guestbook](ksonnet-guestbook/) | The guestbook app as a ksonnet app |
| [helm-guestbook](helm-guestbook/) | The guestbook app as a Helm chart |
| [jsonnet-guestbook](jsonnet-guestbook/) | The guestbook app as a raw jsonnet |
| [jsonnet-guestbook-tla](jsonnet-guestbook-tla/) | The guestbook app as a raw jsonnet with support for top level arguments |
| [kustomize-guestbook](kustomize-guestbook/) | The guestbook app as a Kustomize 2 app |
| [pre-post-sync](pre-post-sync/) | Demonstrates Argo CD PreSync and PostSync hooks |
| [sync-waves](sync-waves/) | Demonstrates Argo CD sync waves with hooks |
| [helm-dependency](helm-dependency/) | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo |
| [sock-shop](sock-shop/) | A microservices demo app (https://microservices-demo.github.io) |
| [plugins](plugins/) | Apps which demonstrate config management plugins usage |
| [blue-green](blue-green/) | Demonstrates how to implement blue-green deployment using [Argo Rollouts](https://github.com/argoproj/argo-rollouts)
| [apps](apps/) | An app composed of other apps |

**Note: Repository Archival Notice**

As of this announcement, please be informed that this repository [https://github.com/JudahSan/argocd-example-apps](https://github.com/JudahSan/argocd-example-apps) has been archived and will no longer receive active updates or maintenance. The repository will remain accessible for reference and historical purposes, but no further changes or contributions are expected.

We encourage you to explore the provided content and leverage it as a learning resource. For the most up-to-date information and active contributions, we recommend visiting the original source repository [https://github.com/mabusaa/argocd-example-apps](https://github.com/mabusaa/argocd-example-apps) and engaging with the Argo CD community directly.

Thank you for your interest and participation in this repository. We hope you find the information valuable in your journey to mastering Argo CD and advancing your GitOps practices.
