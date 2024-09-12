# acm-policys

* To run this first you need to modify the day-1 regions to which az instances will be places 
* First run the day-2 yaml to setup the infra 
* Run Day-2 yaml second. 
* You need to check ACM if the release version changes 

## Pre Reqs
* Install Red Hat gitops operator. 
* Make sure the gitops SA account is cluster admin
* Once acm is installed for admin will have to set Infra-nodes=3 as a label to the cluster where nodes should be created
