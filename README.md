# Kubernetes_Templates

## kubectl get commands

    kubectl get pod
    kubectl get pod --watch
    kubectl get pod -o wide
    kubectl get service
    kubectl get secret
    kubectl get all

## kubectl debugging commands

    kubectl describe pod pod-name
    kubectl describe service service-name
    kubectl logs pod-name

## give a URL to external service in minikube

    minikube service *NAME-OF-SERVICE*
