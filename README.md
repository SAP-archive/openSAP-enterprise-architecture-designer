![](https://img.shields.io/badge/STATUS-NOT%20CURRENTLY%20MAINTAINED-red.svg?longCache=true&style=flat)

# Important Notice
This public repository is read-only and no longer maintained. For the latest sample code repositories, visit the [SAP Samples](https://github.com/SAP-samples) organization.

# openSAP Course: Introduction to SAP Enterprise Architecture Designer

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/openSAP-enterprise-architecture-designer)](https://api.reuse.software/info/github.com/SAP-samples/openSAP-enterprise-architecture-designer)

### Description
This repository contains the results of various exercises in the openSAP course HSEAD-1.

### Requirements
You need to have access to SAP Enterprise Architecture Designer. SAP Enterprise Architecture Designer is an XSA application running on the SAP HANA XSA development stack
It allows to deployment on-premise as well as in the cloud. So there are various availabilities of the product:
- SAP EA Designer as part of SAP HANA2 full use with 5 concurrent users included (unlimited "read" users)
- SAP EA Designer as part of SAP HANA2 Express with a 1 concurrent user included (unlimited "read" users)
- SAP EA Designer CE (Cloud Edition) 

### Download and Installation
1. Download this repository and unpack it.
1. The files from the single sections can be imported into EA-Designer using the import function in the **Browse** mode.

### Known Issues
Older versions of SAP EA Designer had a faulty generation of associations. Make sure relation columns are in the form:
 - correct  "targettable_1" "targettable"   the generator of older version do the 
 - false  "targettable"   "targettable"   need to be manual adjusted
it is not allowed to have the same name for column and join

### License
Copyright (c) 2018-2020 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
