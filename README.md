# sap-2012
This is a repository dedicated to the UK Standard Assessment Procedure (or SAP calculation) for dwellings. This is the method used to produce Energy Performance Certificates for homes.

SAP comprises:
- input variables collected by an assessor
- look up tables containing the factors to apply for a given material or system found to be present in a home
- a step by step procedure for benchmarking annual space heating and hot water requirements

This repo contains 'python friendly' versions of the look up tables and a script for running the procedure itself.

Note that many of the tables have fields which depend on the model of the house developed in the procedure. For example, the value in the table is a function of the volume of water storage in the hot water system - this is an input into the model of the house. 

The next stage of this work will test the sensitivity of the procedure to varying each guestimate put into the model by assessors.

More information on the procedure and the source of the look up tables can be found here:
https://www.bregroup.com/sap/standard-assessment-procedure-sap-2012/

The UK government maintains this page explaining the SAP.
https://www.gov.uk/guidance/standard-assessment-procedure#sap-2012
