# Project 5 - Data Pipelines with Airflow

A music streaming company, Sparkify, has decided that it is time to introduce more automation and monitoring to their data warehouse ETL pipelines and come to the conclusion that the best tool to achieve this is Apache Airflow.

## Apache Airflow

Airflow is a super feature rich engine compared to all other solutions. Not only we can use plugins to support all kinds of jobs, ranging from data processing jobs: Hive, Pig (though we can also submit them via shell command), to general flow management like triggering by existence of file/db entry/s3 content, or waiting for expected output from a web endpoint, but also it provides a nice UI that allows us to check our DAGs (workflow dependencies) through code/graph, and monitors the real time execution of jobs.

Credits: [Shawn's Pitstop](https://xunnanxu.github.io/2018/04/13/Workflow-Processing-Engine-Overview-2018-Airflow-vs-Azkaban-vs-Conductor-vs-Oozie-vs-Amazon-Step-Functions/)

### Prerequisites

```
Apache Airflow 1.10.2
Python 3.6.3
```

## Data Sources

Data resides in two directories that contain files in JSON format:

1. Log data: s3://udacity-dend/log_data
2. Song data: s3://udacity-dend/song_data


## Data Quality Checks

```
Give an example
```

## Scripts Usage

```
Give an example
```

## Built With

* [Python 3.6.2](https://www.python.org/downloads/release/python-363/) - Used to code DAG's and its dependecies
* [Apache Airflow 1.10.2](https://airflow.apache.org/) - Workflows platform

## Authors

* **Guilherme Furukawa** - *Initial work* - Udacity student

