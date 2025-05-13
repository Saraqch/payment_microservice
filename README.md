# MICROSERVICIO PAYMENT

## ÍNDICE
1. [Descripción](#1-descripción)
2. [Tecnologías utilizadas](#2-tecnologías-utilizadas)
3. [Estilo de Arquitectura](#3-estilo-de-arquitectura)
4. [Patrón de Arquitectura](#4-patrón-de-arquitectura)
5. [Estructura del proyecto](#5-estructura-del-proyecto)
6. [Base de Datos](#6-base-de-datos)
7. [Como levantar el proyecto](#7-como-levantar-el-proyecto)
8. [Como construir la imágen](#8-como-construir-la-imágen)
9. [Cómo levantar la imagen con Docker Compose](#9-cómo-levantar-la-imagen-con-docker-compose)
10. [Variables de entorno .ENV](#10-variables-de-entorno-env)
11. [Documentation](#11-documentation)

## 1. Descripción

Este es un microservicio de payment (Targeta de crédito), para su desarrollo aplicaremos la Arquitectura Hexagonal.

## 2. Tecnologías utilizadas
    - Spring boot 3.4.5
    - Java 17
    - Maven 3.9.9

## 3. Estilo de Arquitectura

- Microservicios

## 4. Patrón de Arquitectura

- Arquitectura Hexagonal

## 5. Estructura del proyecto

- Infraestruture
- Application
- Domain

## 6. Base de Datos

- MySql

## 7. Como levantar el proyecto

Terminal

- Si no tienes instalado maven:
    ```sh
    ./mvnm spring-boot:run
    ```
- Si tienes instalado maven:
    ```shell
    mvn spring-boot:run
    ```

## 8. Como construir la imágen

```shell    
  docker build -t billing-latest .
```

## 9. Cómo levantar la imagen con Docker Compose

Aquí agrega la descripción...

## 10. Variables de entorno .ENV

Agregamos una descripción aquí en caso de que nuestro microservice use variables de entorno...

## 11. Documentation

Agregamos en enlace de SWAGGER, para documentar nuestra Api Rest usaremos esta herramienta Swagger.
    
     