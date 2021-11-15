# Spring Boot Admin on Kubernetes

This demo project uses Spring Boot Admin to monitor microservices on Kubernetes.  

The project contains the following
   * Spring Boot Admin
   * 2 simple microservices
    * BankingService
    * CurrentAccountService
   
 * scripts for setting up and configuring cluster on AKS
   * createAKSClusterAndACR.sh - create resource group, cluster and container registry
   * deployAndExposeMicroservices.sh - uses Kubectl to create a namespace, create deployments for each microservice, create a Service for each microservice and create an Ingress for exposing the Linkerd dashboard