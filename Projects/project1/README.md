# project1

Jupyter notebook environment with standard data science packages, Bokeh, and Neo4j.

## Run
```bash
export NB_UID=$(id -u) && docker compose up --build
```
## Port frward
 ssh -L 8888:localhost:8888 jpolizzi@gu-jpolizzi-lv 

- Jupyter: `http://<remote addy>:8888`
- Neo4j browser: `http://<remote addy>:7474`
- Neo4j bolt: `bolt://localhost:7687` (user: `neo4j`, password: `password`)

## Stopping
```bash
docker compose down
```
