VirtualAssembly/SparqlBundle 
===============

This is a simple Sparql bundle in WORK IN PROGRESS. 
There is not a stable version for the moment.

There aim is generate Sparql query.

How to use it 
===============

If you want to test this bundle, you need to add in your main composer :
- in require :

    "VirtualAssembly/SparqlBundle" : "dev-master"
    
- create a repositories section at the same level of require

	"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/assemblee-virtuelle/SparqlBundle.git"
        }
    ],