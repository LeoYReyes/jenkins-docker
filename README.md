# jenkins-docker
 
Automated Jenkins setup in a Docker container.

## Getting started

## How-to

### Get a new list of plugins
```
curl -s -k "http://admin:admin@localhost:8080/pluginManager/api/json?depth=1" | jq -r '.plugins[].shortName' | tee plugins.txt
```