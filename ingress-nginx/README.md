# Nginx controller for Ingress

An Ingress resource is just a definition for your cluster how to handle ingress traffic. It needs an Ingress Controller to actually process these definitions; creating an Ingress resource without having deployed an Ingress controller will not have any effect. So deploy nginx:

```sh
kubectl apply -f ingress-nginx.yaml
```



---

## Sources:

- [ingress with cermaanger](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-with-cert-manager-on-digitalocean-kubernetes)

