# Kubernetes Example Exercises

Each example in this folder is intended to provide a troubleshooting scenario exercise.

If you are working through these exercises in a take home fashion, please follow these steps.

1. Clone this repo to your machine
2. Create a Kubernetes cluster you can access
   - This can be on a public cloud using any managed cluster, but it does NOT need to be in the cloud or cost anything
   - You can create a local cluster using:
     - [minikube](https://minikube.sigs.k8s.io/docs/) (our preference among the somewhat advanced choices but not required)
     - [kind](https://kind.sigs.k8s.io/)
     - [k0s](https://k0sproject.io/)
     - [Docker Desktop](https://docs.docker.com/desktop/kubernetes/)'s built in Kubernetes cluster (easiest cluster to get going, and perfectly acceptable for this purpose)
     - or any other arrangement you can come up with that gives you access to a Kubernetes cluster
3. Install Kubernetes management tools for accessing and troubleshooting your cluster
   - The basic tool of course is [kubectl](https://kubernetes.io/docs/tasks/tools/), but we also _highly_ recommend trying out [k9s](https://k9scli.io/)
4. Please work through the exercises and share your answers as well as your thought process for finding a solution
   - Create a branch in this git repo with your name, and commit a file (or files) that provide your solution to each scenario
   - This can be as simple as a fixed version of a manifest, or sometimes an inclusion of a missing item
   - Include an ANSWER.md file that describes what you found, your solution, and any other details that will help us understand how you approached the problem
   - If possible / appropriate, screenshots or other evidence that you were able your fix working
   - Be ready to share a link to your branch that includes your solutions

_IMPORTANT_ Please do not post answers directly to the main branch on this repo or in other public forums. This is intended for job interview discussion.
