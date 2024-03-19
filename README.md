https://classroom.emeritus.org/courses/8898/pages/airflow?module_item_id=1486499

# curl the docker file

`curl 'https://airflow.apache.org/docs/apache-airflow/2.1.1/docker-compose.yaml' -o docker-compose.yaml`
doing this with command prompt errors with
curl: (3) URL rejected: Port number was not a decimal number between 0 and 65535
so open wsl and do it there

Open the docker-compose.yaml file using VS Code. Set the AIRFLOW**CORE**LOAD_EXAMPLES environment variable equal to false. Save and close the file.

run the `docker-compose up`
this creates some folders and runs containers

go to http://localhost:8080/
“airflow” for both the username and password