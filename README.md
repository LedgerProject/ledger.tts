## Ledger TTS (Time Stamping Service)

This project builds and deploy a 2-tier application that uses the Fabric network to provide a Time Stamping Service. 

The 2-tier application consists of the following components:

* RESTful API, running as a Node.js Express application, using the Hyperledger Fabric Client SDK to query 
and invoke chaincode
* Fabric Chaincode, written in Node.js, deployed to a Hyperledger Fabric network

## Getting started

To deploy the chaincode and start the RESTful API server, follow the 
README instructions in parts 1-2, in this order:

* [Part 1:](chaincode/README.md) Deploy the chaincode. 
* [Part 2:](rest-api/README.md) Run the RESTful API server. 

## Acknowledgements

LEDGER has received funding from the European Union’s Horizon 2020 research and innovation programme under the Grant Agreement no 825268.

## Links

https://ledgerproject.eu/

## License

This library is licensed under the Apache 2.0 License. 
