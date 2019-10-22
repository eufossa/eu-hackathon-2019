# FLUX TL

## About

Transport Layer for Fisheries Language Universal eXchange (FLUX TL)

Features:
* Messaging integration system among MS and other international parties.
* To exchange Fisheries Control data (e.g. vessel positions, fishing activity)
* Using an international standard (UN/FLUX)

Every node of the network runs a FLUX TL end node. Commission runs a central node to which all are connected.

FLUX TL has 4 components: WS, WebApp, BRIDGE and NAFConnector.

Recent work on FLUX TL includes:
* Increase performance (from 3 msg/sec to 60-80 msg/sec)
* Internal refactoring (better DB use, removal of Quartz, decoupling elements)
* Monitoring site (Angular)
* Docker 
* Faster upgrades (Liquibase) 

## Goals and achievements

The work in the Hackathon did not involve coding, but a reflection (without daily pressure) on the future of the system. The features that were deemed of more importance for the future were:

* Simplify the FLUX node configuration
* Optimize protocol
* Improved message delivery confirmation
* Decouple components
* Move FluxTL to the cloud
