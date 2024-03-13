# Intsurfing test task

## How to run
- Have a Docker installed
- Run the [almondsh](https://almond.sh/) - Scala kernel for Jupyter:
    - Go to the `docker-compose-almondsh.yml` file and change \
    `/full/path/to/your/project/dir/` in `volumes` section
    - Run kernel with command:
    ```sh
    docker compose -f docker-compose-almondsh.yml up
    ```
- Connect to the almondsh kernel, see log output from docker container
- Run code as usual Jupyter Notebook
