# webinar-cluster-manager

## Red Hat Openshift
<pre>
- By default, Red Hat Openshift cluster supports 3 master nodes and multiple worker nodes
- Each master node, hosts the control plane components
  - API Server (Static Pod)
  - etcd ( key/value database )
  - Controller Managers ( collection of many controllers )
  - scheduler
- Typically, all the user applications are deployed into the worker nodes
- Optionally, we could also configure master nodes to allow deploying user applications onto master nodes
- If any of one/two master node goes down, still the openshift cluster works fine with the third master node
</pre>  

## Openshift Cluster Management
<pre>
- Openshift offers managing all your Red Hat Openshift clusters from centralized webconsole
- You could create, edit, update and delete cluster from Cluster Manager
- Helps the Openshift administrators to manage multiple openshift cluster
- these openshift cluster could run in on-prem, public clouds ( AWS, Azure, GCP, etc.,)
  
</pre>
