# Kube-News 
(by fabricioveronez)

<p align="end">January 2024</p>

A web application for publishing news. This project was forked from the repository <a href="https://github.com/KubeDev/kube-news">kube-news</a> during the Docker and Kubernetes Immersion event. In this event, features related to Docker containers for this app and its database were developed and used to run it locally without installing any dependencies in the local environment.

The contributions for the original project are in Dockerfile and Compose yaml for creating containers that handle database and app execution.


<img src="https://github.com/MauroImamura/images/blob/main/Kubenews_page.jpg"></img>

### Setup
It's necessary to create a Postgre database and set the connection between app and db using the following environment variables:

DB_DATABASE => database name.

DB_USERNAME => database user.

DB_PASSWORD => database password.

DB_HOST => database address.
