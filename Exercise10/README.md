# Exercise 10: Multi-Node Kubernetes Cluster with Multiple Applications and ReplicaSets

## Objective

To deploy multiple Flask applications on a three-node Minikube cluster using Kubernetes Deployments, ReplicaSets, and Services.

## Technologies Used

- Python
- Flask
- Docker
- Kubernetes
- Minikube
- Git and GitHub

## GitHub Repository

https://github.com/BinduG07/DEVOPS/tree/main/Exercise10

## Project Structure

```text
Exercise10/
├── product_catalog.py
├── shopping_cart.py
├── Dockerfile.product
├── Dockerfile.shopping
├── product_catalog_deployment.yaml
├── shopping_cart_deployment.yaml
├── product_catalog_service.yaml
├── shopping_cart_service.yaml
├── README.md
└── Screenshots/
    ├── add items to cart.png
    ├── docker images.png
    ├── build docker.png
    ├── product catalog.png
    ├── shopping cart service.png
    ├── shopping cart.png
    ├── shopping products.png
    └── start minikube.png
```

## Applications

1. **Product Catalog:** Displays product details through the `/products` endpoint and runs with 2 replicas.
2. **Shopping Cart:** Allows users to add and view cart items through the `/cart` endpoint and runs with 3 replicas.

## Implementation

1. Created a three-node Minikube cluster.
2. Developed two Python Flask applications.
3. Created Dockerfiles and built Docker images.
4. Loaded the images into the Minikube cluster.
5. Created Kubernetes Deployment YAML files with the required replicas.
6. Configured pod anti-affinity to distribute pods across nodes.
7. Exposed both applications using NodePort services.
8. Tested the applications using curl.

## Verification Commands

```bash
kubectl get nodes
kubectl get deployments
kubectl get replicasets
kubectl get pods -o wide
kubectl get services
```

## Result

Both Flask applications were deployed on the three-node Kubernetes cluster with the required replicas and NodePort services.

## Conclusion

This exercise demonstrates multi-node Kubernetes deployment, containerization, ReplicaSet management, pod distribution, and service exposure.

## Screenshots

The `Screenshots/` folder contains screenshots of the cluster, Docker images, deployments, ReplicaSets, pod distribution, services, and application
