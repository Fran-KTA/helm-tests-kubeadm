# helm-tests-kubeadm
Helm Charts tests over kubeadm deployed single control plane cluster

* local-path-provisioner
  - Solo la carpeta Deploy (helm chart) del repo original de Rancher

## Recordermos el orden
- nfs/local provisioner(s)
  * Ajustar nfs.server en nfs provider
  * Ajustar nodePathMap.node.paths en local-path provider
- prometheus-operator
  * Ajustar ingress host(s)
- nginx-ingress-controller
- mariadb
- wordpress
  * Ajustar ingress host
