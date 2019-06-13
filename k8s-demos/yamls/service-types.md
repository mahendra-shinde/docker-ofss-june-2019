Service Types:

1. NodePort
    Expose your SERVICE on All NODEs with COMMON port to OUTSIDE
    the cluster.

2. ClusterIP
    Do Not expose service to outside, use internal ip and port.

3. External Name
    Expose your SERVICE to external IP / Domain name.
    PRODUCTION USE!!

4.  Load Balancer
      ONLY ON CLOUD (AKS, EKS, GKS)
        On Azure Kubernetes Services, It maps itself to new Azure Load Balancer
