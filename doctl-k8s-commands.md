doctl auth init

doctl account get 

doctl kubernetes cluster create <cluster-name> --region <name> --size s-2vcpu-4gb --count 3

doctl kubernetes cluster update <cluster-name> --count 1


doctl kubernetes cluster kubeconfig save <cluster-name>

doctl kubernetes cluster kubeconfig show <cluster-name>

doctl kubernetes cluster kubeconfig show <cluster-name> > ~/k8s-for-devs/kubeconfig.mycluster




doctl compute droplet list

doctl compute droplet delete <droplet-id>

doctl compute droplet get <droplet-id>
