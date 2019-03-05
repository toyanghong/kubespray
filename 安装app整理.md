## kd token
 ``` 
  kubectl -n kube-system describe $(kubectl -n kube-system get secret -n kube-system -o name | grep namespace) | grep token
   ``` 
## https 默认设置
 ``` 
 nginx.ingress.kubernetes.io/backend-protocol: "HTTPS"
   ``` 
