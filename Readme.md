# BSI Flex 355
BSI Flex 335 specifies the interfaces within a SAPIENT (Sensing for Asset Protection with Integrated Electronic Networked Technology) system.  Specifically, it addresses the interfaces between edge nodes, the fusion node and any message handling application.  

This repository provides protobuf aligned to the interfaces defined in BSI Flex 335

## Latest Standard
The latest standard document can be download from BSI: https://knowledge.bsigroup.com/products/sapient-network-of-autonomous-sensors-and-effectors-interface-control-document-specification/standard

## SAPIENT Summary
*For more details see the Standard above*

SAPIENT is a concept that describes a system comprised of a suite of autonomous edge nodes, which may have sensor or effector (or both) capabilities combined with remote modules that perform fusion and node tasking. 
The key principles of SAPIENT are:

1) 	local autonomy at the edge; i.e. local processing of sensor data where the nodes are sensor edge nodes ;
2) 	the transmission of information (the output of the processing) rather than the raw data from the sensor edge node;
3) 	the fusion of information at remote fusion nodes and the generation of tasking messages for taskable edge nodes (sensor edge nodes or effector nodes), and;
4) 	local autonomous execution of received taskings at taskable edge nodes (sensor edge nodes or effector nodes).

When combined as a system, these principles give the following desirable features:
*	reduction in operator workload during monitoring activities; 
*	improved autonomy for decision making; 
*	improved autonomy for management of edge nodes;
*	lower bandwidth requirements for network traffic, and;
*	node modularity – nodes of different types (particularly sensor edge nodes) use the same interface for communication whatever their modality.

## Acknowledgements
This BSI Flex was sponsored by the UK Ministry of Defence. Its development was facilitated by BSI Standards Limited and it was released under licence from The British Standards Institution. It came into effect on May 31st 2023
Acknowledgement is given to Paul Thomas, Dstl, as the lead technical author, and the following organizations that were involved in the development of this BSI Flex as members of the Advisory Group:
* Createc
* Defence UAS Capabilities 
* DSTL
* Exensor
* L3 Harris
* Leonardo
* Marss
* MBDA
* Metis Aerospace
* OSL
* Overview
* Plextek
* Qinetiq
* Roke
* 
The British Standards Institution retains ownership and copyright of this BSI Flex. BSI Standards Limited, as the publisher of the BSI Flex, reserves the right to withdraw or amend this BSI Flex on receipt of authoritative advice that it is appropriate to do so.
This BSI Flex is not to be regarded as a PAS or British Standard. 
The BSI Flex process enables a standard to be rapidly developed, on an iterative basis, in order to fulfil an immediate stakeholder need. A BSI Flex can be considered for further development as a PAS or British Standard, or constitute part of the UK input into the development of a European or international standard.
The content in this version is part of an iterative process. It is likely to change from time to time with subsequent iterations.
