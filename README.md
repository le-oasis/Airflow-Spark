# Airflow/Spark Dockerfile

## Dockerfile: Build the Image.
- A `Dockerfile`  is a text document that contains all the commands a user could call on the command line to assemble an image. 

- `Dockerfile` that contians installations of `JAVA-JDK.v11`, `ApacheSpark.v3.2.0`, `Hadoop.v3.2`, & other dependencies built on top of `Airflow.v.2.2.3`.

- navigate to the `docker-airflow` directory, this is where the `Dockerfile` is located:

    - `Dockerfile` is a `.dockerfile` file that contains the instructions to build the image.
    - `docker` --> `airflow-setup` --> `Dockerfile`.
    
- It will take about ***10minutes*** to build, depending on yor internet speed / platform you use to build the image.

- Run the following command to build the image:

```
docker build --rm --force-rm -t oasis/airflo/spark . 
```
