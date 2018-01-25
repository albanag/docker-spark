### What's in here?

The following Dockerfile is used to create a Docker image running Apache Spark 2.2.0 inside Debian 8. It includes Java 8 and the necessary Python libraries to run PySpark and Jupyter Notebook.

### How to build

By running the following super simple script one can create the Docker image:

```
./build.sh
```

### Final notes

The resulting image can be also found in Docker Hub. To use it directly:

```
docker pull albanag/docker-spark
```

