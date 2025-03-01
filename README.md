HelloWorld Spring Boot Project

Overview

This is a simple Spring Boot REST API demonstrating various HTTP methods like GET, POST, and PUT while handling query parameters, path variables, and JSON request bodies.

Topics Covered

Spring Boot Basics (@RestController, @RequestMapping)

REST API Methods (@GetMapping, @PostMapping, @PutMapping)

Handling Parameters (@RequestParam, @PathVariable, @RequestBody)

DTO (Data Transfer Object) Usage

API Endpoints

Method

Endpoint

Description

GET

/hello

Simple greeting message

GET

/hello/query?name=John

Greeting using query parameters

GET

/hello/param/John

Greeting using path variables

POST

/hello/post

Accepts JSON request body

PUT

/hello/put/John?lastName=Doe

Updates name using path & query params