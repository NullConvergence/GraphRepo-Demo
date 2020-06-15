# GraphRepo Demo
This notebook contains a demo of the [GraphRepo](https://github.com/NullConvergence/GraphRepo) project.


A screencast of this demo is available on [Youtube](https://www.youtube.com/watch?v=x1ha0fRltGI).

In order to clone the project and it's submodules, use:

```
$ git clone --recurse-submodules https://github.com/NullConvergence/GraphRepo-Demo
```

The project assumes you have Docker, Python, Pip and Jupyter installed. In order to run a Neo4j Docker instance, use:

```
$ docker run --publish=7474:7474 --publish=7687:7687 --volume=$HOME/neo4j/data/exp:/data --volume=$HOME/neo4j/logs/exp:/logs --env NEO4J_AUTH=neo4j/neo4jj  neo4j:3.0
```

Then you can run it using:

```
$ jupyter notebook
```
