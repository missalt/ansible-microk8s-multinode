# Ansible Playbook for MicroK8s Multi-Node Cluster creation

This ansible playbook (and the corresponding inventory file) can be used to join multiple (virtual or physical) hosts together to create a Kubernetes-Cluster.

Please keep in mind that this playbook was developed for the quite specific Use-Case of creating a K8s-Cluster out of multiple Raspberry-Pis without persistent storage.
These Pi's are used for testing purposes and NOT for Production, so parts of this script might have some parts in them that are questionable security-wise.

So, this script is merely a starting point if you want to do it "the right way". Feel free to contribute or fork this project, I'm also always glad to help if youre facing problems yourself.


