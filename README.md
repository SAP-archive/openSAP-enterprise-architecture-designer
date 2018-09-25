# openSAP-enterprise-architecture-designer
# openSAP-hsead-1


### Description
This repository contains the results of various exercises in the openSAP course HSEAD-1.

### Requirements
You need to have access to an Enterprise Architecture Designer
Enterprise Architecture Designer is an XSA application running on the HANA XSA development stack
It leverages the promize to deploy on-premise as well as in the cloud
So there are various availablities of the product
- EA-Designer as part of SAP HANA2 full use with 5 concurrent users included (As may as wanted reading users)
- EA-Designer as part of SAP HANA2 Express with a 1 concurrent user included (As may as wanted reading users)
- EA-Designer CE (Cloud Edition) 
### Download and Installation
You should download this repository and unpack it.
The files from the single sections can be imported into EA-Desiger using the import function in the **Browse** mode
### Known Issues
older version of EA-Designer do have a errorous generation of assocciation. Make sure relation columns are in the form
 - right version "targettable_1" "targettable"   the generator of oder version do the 
 - wrong version "targettable"   "targettable"
*it is not allowed to have the same name for column and join*

### License
Copyright (c) 2018 SAP SE or an SAP affiliate company. All rights reserved.
