Simple Docker Compose based on [this repo](https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker), it contains some examples on how to use the Spark Neo4j Connector.


To start the project, just run:

```shell
# -d is for detached mode (runs everything in background)
docker compose up -d
```

To check the status of the cluster through the spark UI, just connect to:
```shell
http://<ip_address_of_the_machine>:8080
```

If you want to code directly from the cluster, connect to Jupyterlab on:
```shell
http://<ip_address_of_the_machine>:8888
```

From Jupyterlab, you will see that in the workspace there are different Python Notebooks that will guide you on your first steps using the Neo4j Connector for Spark.