# QA4LOV
QA over Linked Open Vocabularies

Demo at http://212.101.173.21:3333/dataset/bdo/qa

## List of dependencies

- Quepy Library 
- Python 2.7
- Flask 
- Datalift or Sesame or fuseki to store LOV dataset

## How to launch the src/webapp
- Download the repository `src/webapp`
- Launch Datalift  containing an instance of [BDO dataset](http://212.101.173.21:3333/dataset/bdo/) published at `http://localhost:9091/sparql/data`. 
- If different endpoint, change the value in the file `main.py` in Line 15: `sparql = SPARQLWrapper("http://fuseki:3030/sparql/data")` to the corresponding endpoint
- `$ ./app.py`  
- The server starts at http://127.0.0.1:5000/
