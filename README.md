# Openstack project using Heat Orchestration
- Implemented a two-tier architecture with public and private subnets using Neutron
- Deployed three Nova instances in private subnet and Load balancer at the public subnet
- The instances can access the internet through bastion host deployed in public subnet and with route table configured accordingly
- All this is deployed through kubernetes cluster using a HOT template

# Architecture Diagram of the project
![image](https://github.com/Krishks369/Loadbalancer-on-openstack/assets/71367204/d5991fbc-06c5-495b-bd2a-4426a809526a)

(note - the red nodes are because of insufficient resources in my laptop)
