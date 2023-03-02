# Empresarial_full_stack

## Introduccion
El siguiente proyecto tiene como objetivo, la elaboracion de una aplicacion full stack con spring boot y angular, recopilando los conocimientos obtenidos durante la electiva de aplicaciones empresariales, buscando aplicar las mejores practicas y diversas tecnologias.

El presente readme presentara la documentacion necesaria a modo de una guia explicativa del proceso.

## Problematica
La maestría en computación necesita la implementación de una aplicación web que permita gestionar las asignaturas, cursos y estudiantes, así como matricular a los estudiantes en los cursos. Como parte de la arquitectura, se ha desarrollado el siguiente diagrama de clases:
![Diagrama de clases base, recurso 1](https://github.com/edynsonmj/Empresarial_full_stack/blob/main/recursosRM/recurso%201.png)

## Tecnologias

### Tecnologias back
+ Java: lenguaje base backend.
+ Spring boot: framework para la construccion de servicios web full rest.
+ Hibernate: ORM basada en JPA, para la manipulacion del acceso a la base de datos.
+ JPA: Especificacion para el manejo de la persistencia en java.

### Tecnologias front
+ JavaScript: lenguaje base frontend.
+ Angular: framework para la construccion de aplicaciones web de pagina unica, single page application.

## Proyecto backend: Proceso de construccion e instructivo.
+ JDK 17.
+ Spring version 3.1.0 snapshot

### Crecion del proyecto.
Mediante el editor de codigo visual studio code se han siguido los siguientes pasos:
+ pulsar: ctrl + shift + p, para abrir una terminal de comandos.
+ seleccionar: >spring Initializer: create a maven project.
+ seleccionar version de spring: 3.1.0 (snapshot).
+ seleccionar lenguaje: java.
+ id del grupo o dominio: co.edu.unicauca.core
+ identificador del artefacto: back_empresarial
+ tipo de empaquetado: jar
+ version java: JDK 17.
+ seleccionar depencias:
  + Spring boot devtools: herramintas de desarrollo para spring.
  + Spring web: para el desarrollo web con rest full, tomcat, mvc etc.
  + MySQL driver sql: driver de conexion a base de datos.
  + Spring data JPA sql: manejo de la persistencia.

## Proyecto frontend: Proceso de construccion e instructivo.

### Creacion del proyecto.
