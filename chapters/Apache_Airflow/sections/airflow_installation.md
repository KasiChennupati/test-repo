# Apache Airflow Installation
(airflow_main_page_chapter)=

In the previous section we saw what we have in the official page of Airflow

Let's now see How to actually set this up in different environments

- [Docker](airflow-in-docker)
- [Linux](airflow-in-linux)
- [Windows](airflow-in-windows)
- [MacOS](airflow-in-macos)
- [Anaconda](airflow-in-anaconda)

(airflow-in-docker)=
## Airflow in Docker

Apache Airflow can be installed in Docker using the following Dockerfile

(airflow-in-linux)=
## Airflow in Linux

In Progress

(airflow-in-windows)=
## Airflow in Windows

In Progress

(airflow-in-macos)=
## Airflow in MacOS

In Progress

Sorry! need help with MacOS setup.But, docker is suggested for Mac Users in general for softwares that support docker.

(airflow-in-anaconda)=
## Airflow in Anaconda

Airflow can be installed in anaconda using the conda virtual environments

```yml
    name: env_airflow
    channels:
    - conda-forge
    - defaults
    dependencies:
    - python>=3.10
    - pip>=23.1.2
    - pip:
        - apache-airflow
        - apache-airflow[google-auth]
        - apache-airflow[graphviz]
        - apache-airflow[password]
        - apache-airflow[ldap]
        - apache-airflow[virtualenv]
        - apache-airflow[apache-cassandra]
        - apache-airflow[apache-spark]
        - apache-airflow[apache-hdfs]
        - apache-airflow[apache-kafka]

```