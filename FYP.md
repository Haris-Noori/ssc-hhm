==================================================
# SECURING SUPPLY CHAIN
==================================================
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://hyperledger-fabric.readthedocs.io/en/release-2.2/_images/peers.diagram.1.png" width="80%"></a></p>

### A Network has -> Channels

#### Right now, in our network there is only 1 channel:
	ssc (securing-supply-chain)
-----
### There are 3 peers in our SSC channel:
	more about Peers(https://hyperledger-fabric.readthedocs.io/en/release-2.2/peers/peers.html)

	1- Orderer (endorsing peer)
	2- Manufacturer
	3- Supplier
	4- Retailer

### Peers host ledgers and smart contracts(aka chaincode)
### A Legder records all the transactions, generated by chaincode(smart contracts)


----------------=================---------------
## PLAN OF EXECUTION
----------------=================---------------
### MID Presentation:

	- integrate couchdb 
						CouchDB:
							Apache CouchDB is an open-source document-oriented NoSQL database, implemented in Erlang. CouchDB uses multiple formats and protocols to store, transfer, and process its data, it uses JSON to store data, JavaScript as its query language using MapReduce, and HTTP for an API

	- use Fabric-ca as certificate authority 
	- Develop client application (demo test fabric-client-sdk)


	- web app (using fabric-client-sdk) + REST-API for mobile
	- mobile app (will use by peers):
			- Manufacturer (will recieve and approve/disapprove the transaction requests)
			- 