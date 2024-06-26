Open5GS is a Open Source implementation for 5G Core and EPC, i.e. the core network of LTE/NR network (Release-17). 
Open5GS can be deployed on OpenShift via Operators or Helm chart or GitOps approach. 
It requires sctp protocol to be enabled on CoreOS level. 
You can enable sctp on OpenShift  e.g. https://github.com/ansonmez/ocpopen5gs/blob/main/load-sctp-module.yaml 
SCTP enablement on OpenShift requires machineconfig configuration. 

