#DC Jeeves Feature Pipeline

###v1.0
**WF**
	*Spark message —> [Spark bot] —- REST API — > [REST API for UCS Director ] —> UCS REST interface
**Demo**
	*Pre-setup UCSD w/deveopment key (preinsatleld UCSD workflows)
	*deploys dcjeeves_spark to MANTL
	*deploy dcjeeves_app to MANTL
**LANG** 
	*Initial language support


###v1.1
**WF**
	*UCS Director <—> [watch dog] <—-> Spark
	

###V1.2
**Demo**
	*auto deploy of UCSD workflows

###v1.3
- 

<BR><BR>
Demo
1. Deploy app
2. Register Datacenter
3. show case
4. De-register

dcjeeves < COMMAND > <OBJECT> on <ENVIRONMENT> at <CLOUD>


CLOUD
	UCSD instance

ENVIRONMENT
	UCSD VPC

COMMAND


v1.0
dcjeeves  start vm-name on prod at ucsd
	starting vm-name
dcjeeves  stopt vm-name on prod at ucsd
	stopping vm-name
dcjeeves  status vm-name on prod at ucsd
	vm-name running| stopped
dcjeeves list vms on prod at ucsd
	vm-list

v1.1

v1.2
dcjeeves list vms max 10 on prod at ucsd
dcjeeves list vms starting with apple on prod at ucsd



Workflow name
DCJEEVES-VMSTART
	Input - VPC
	VM - Name

DCJEEVES-VMSTOP
	Input - VPC
	VM - Name

DCJEEVES-VMSTATUS
	Input - VPC
	VM- Name
	
