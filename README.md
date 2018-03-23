# k8s-images
For running kubeadm without an internet connection

For running kubeadm without an internet connection you have to pre-pull the required master images for the version of choice:

Image Name	v1.8 release branch version	v1.9 release branch version
k8s.gcr.io/kube-apiserver-${ARCH}	v1.8.x	v1.9.x
k8s.gcr.io/kube-controller-manager-${ARCH}	v1.8.x	v1.9.x
k8s.gcr.io/kube-scheduler-${ARCH}	v1.8.x	v1.9.x
k8s.gcr.io/kube-proxy-${ARCH}	v1.8.x	v1.9.x
k8s.gcr.io/etcd-${ARCH}	3.0.17	3.1.10
k8s.gcr.io/pause-${ARCH}	3.0	3.0
k8s.gcr.io/k8s-dns-sidecar-${ARCH}	1.14.5	1.14.7
k8s.gcr.io/k8s-dns-kube-dns-${ARCH}	1.14.5	1.14.7
k8s.gcr.io/k8s-dns-dnsmasq-nanny-${ARCH}	1.14.5	1.14.7
