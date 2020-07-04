# docker-airflow

This repository contains **Dockerfile** of [apache-airflow](https://github.com/apache/incubator-airflow).

The goal is to make a light build of Airflow - minimizing RAM usage and making it suitable for cheap single-board computers and basic cloud VMs.
Build will be tested on *Rapsberry Pi 3 A+* and *Google Cloud Platform F1-micro* instance (offered in Free Tier). 

## Background

HERE Write something about:
* Raspberry Pi 3A+ (RAM, ARM, speed)
* GCP F1-micro (RAM, 0.2 CPU, speed)

## Installation

## Build

## Usage

## Install custom python package

- Create a file "requirements.txt" with the desired python modules
- Mount this file as a volume `-v $(pwd)/requirements.txt:/requirements.txt` (or add it as a volume in docker-compose file)
- The entrypoint.sh script execute the pip install command (with --user option)

## UI Links

- Airflow: [localhost:8080](http://localhost:8080/)
- Flower: [localhost:5555](http://localhost:5555/)

## Scale the number of workers

## Running other airflow commands
