# Hello World Java

## About The Project

The purpose of this project is to introduce developers to the core concepts of Spring Boot, which simplifies Java web application development.

## Table of Contents

<ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#overview">Overview</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#configuration">Configuration</a></li>
        <li><a href="#running-the-service">Running the service</a></li>
        <li><a href="#running-with-docker">Running with docker</a></li>
      </ul>
    </li>
    <li>
      <a href="#contributing">Contributing</a>
    </li>
 </ol>

## Overview

This is a simple "Hello World" project built with the Spring Framework. It demonstrates the fundamentals of setting up a Spring application, creating a basic REST controller, and handling HTTP requests to display a "Hello, World!" message.

## Features

<div>
  <ul>
      <li> <b>Minimal Configuration:</b> Uses Spring Boot's auto-configuration to reduce boilerplate code.</li>
      <li> <b>Spring Boot Setup:</b> Demonstrates a basic configuration of a Spring Boot application, including dependencies and main class setup.</li>
  </ul>
</div>


## Built With

[![Spring Boot][springboot.com]][springboot-url]
[![Docker][docker.com]][docker-url]

<!-- GETTING STARTED -->
## Getting Started

## Prerequisites

Before you begin, make sure you have the following tools installed on your machine:

- **Java 17 or higher** - [Download Java](https://www.oracle.com/java/technologies/javase-downloads.html)
- **Spring Boot 3.3.2** - [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- **Maven** - [Maven](https://maven.apache.org/install.html)

If you don't have any of these tools installed, follow the provided links to install them.

## Installation

1.- Clone the repository
   ```sh
   git clone https://github.com/Retrofiyer/Java-HelloWorld.git
   cd Java-HelloWorld
   ```
2.- Build project using maven
 ```sh
   mvn clean install
   ```

## Running the service

  ```sh
    mvn spring-boot:run
   ```

Open any browser and type 

  ```sh
    localhost:8080
   ```

## Running with docker

1.- Making Docker Pull or Build docker image

 ```sh
   docker pull retroandre/java-helloworld:latest
   ```
```sh
   docker build -t <any-name> .
   ```
2.- Last make a docker run

 ```sh
   docker run -p 8080:8080 retroandre/java-helloworld:latest # or any-name
   ```
3.- Open any browser and type

 ```sh
   localhost:8080
   ```

## Contributing
I would like you to contribute to this project. Whether it's fixing a bug, adding a new feature or improving the documentation, your help is always welcome. Please email me at `sebitas5225@gmail.com` with all the details for improvement.

<!-- LINKS & IMAGES -->

[docker.com]: https://img.shields.io/badge/Docker-black?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
[springboot.com]: https://img.shields.io/badge/SpringBoot-black?style=for-the-badge&logo=springboot&logoColor=white
[springboot-url]: https://spring.io/projects/spring-boot
[java.com]: https://img.shields.io/badge/Java-black?style=for-the-badge&logo=java&logoColor=white
[java-url]: https://www.oracle.com/java/
