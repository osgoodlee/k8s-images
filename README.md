# k8s-images
For running kubeadm without an internet connection

For running kubeadm without an internet connection you have to pre-pull the required master images for the version 1.9 of choice:
 
k8s.gcr.io/kube-apiserver-${ARCH} v1.9.x

k8s.gcr.io/kube-controller-manager-${ARCH}	 	v1.9.x

k8s.gcr.io/kube-scheduler-${ARCH} 	v1.9.x

k8s.gcr.io/kube-proxy-${ARCH} v1.9.x

k8s.gcr.io/etcd-${ARCH}	3.1.10

k8s.gcr.io/pause-${ARCH}	3.0

k8s.gcr.io/k8s-dns-sidecar-${ARCH}		1.14.7

k8s.gcr.io/k8s-dns-kube-dns-${ARCH}		1.14.7

k8s.gcr.io/k8s-dns-dnsmasq-nanny-${ARCH}		1.14.7

