## Everything here is in Linux Machine or Mac
## 1.open command prompt (use Admin access)
## 2.pipenv install
## 3.pipenv shell
## 1. Download docker. 
## 2. install docker.
## 3. login docker.
## 4. type command: 

docker run -it -p 7474:7474 -p 7687:7687 --env NEO4J_ACCEPT_LICENSE_AGREEMENT=yes --env NEO4J_AUTH=neo4j/clegr-secrets andrewjefferson/myneo4j:3.4.1-enterprise-plus-apoc
