# drill-orcale

## Why

The default `apache drill` have no the oracle jdbc driver.  
This docker image will be include the ojdbc7 by default.

## How

`docker build -t apache/drill-oracle:latest .`  
`docker run -i --name drill-oracle -p 8047:8047 --detach -t apache/drill-oracle:latest /bin/bash`
