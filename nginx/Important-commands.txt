Useful Commands

Scale deployment
kubectl scale deployment <deployment-name> -n <namespace-name> --replicas=5 ##Change the number of replicas to your desired count

##Rolling Updates

Port Forward

kubectl port-forward <service name> -n <namespace> port:service-port --address=0.0.0.0
