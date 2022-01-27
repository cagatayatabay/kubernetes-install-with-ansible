# kubernetes-install-with-ansible

k8s-pre-req.yaml --> before installation you must configure all parameter in master and worker nodes where k8s cluster will be install.
install-runtime.yaml --> cluster installation needs runtime, i used docker for runtime. This playbook prepared for server which have need proxy to connect to internet.
k8s-bootstap.yaml --> start installation with kubeadm
