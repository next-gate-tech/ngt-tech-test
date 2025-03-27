# Kubernetes Tech Test

This repository contains two simple Python “nodes” (scripts) that demonstrate containerization and deployment on Kubernetes:

1. **Random Number Generator** – Generates a random number.  
2. **Subtraction Service** – Accepts two numbers (or a static number) and returns their difference.

Your tasks are:
1. Containerize these nodes.
2. Deploy them to Kubernetes (can use Minikube).
3. Connect them via Kubernetes Services (or similar).

Bonus points: 
- Write an interface in Python to interact with the deployed containers. Consider:
- - Debugging and monitoring the containers.
- - Retrieving outputs from the containers.
- - Any other ways you could make developing against the cluster easier.

## Submission
1. Fork/clone this repository.
2. Create a new branch for your changes (e.g., `feature/k8s-setup`).
3. Implement your solution.
4. Verify that everything runs as expected:
   - Build and run the Docker containers locally.
   - Deploy to a test Kubernetes cluster.
5. Share the link to your repository (or fork) so we can review it.
---
