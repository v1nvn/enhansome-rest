# Awesome REST [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 436,589 | 🐛 68 | 📅 2026-01-28 with stars

A collaborative list of great resources about RESTful API architecture, development, test, and performance. Feel free to contribute to this on-going list.

* [Design](#design)
  * [Guidelines](#guidelines)
* [Standards](#standards)
* [Clients](#clients)
  * [PHP](#php-clients)
  * [Client-side JavaScript](#javascript-clients)
  * [Node.js](#nodejs-clients)
  * [Ruby](#ruby-clients)
  * [Go](#go-clients)
  * [.Net](#net-clients)
  * [Generators](#generators)
* [Servers](#servers)
  * [Directly On Top Of A RMDB](#directly-on-top-of-a-rmdb)
  * [Node.js](#nodejs)
  * [PHP](#php)
  * [Symfony2](#symfony2)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
  * [Java](#java)
  * [Haskell](#haskell)
* [Testing](#testing)
  * [Querying](#querying)
  * [Mocking](#mocking)
  * [Public REST APIs To Use In Tests](#public-rest-apis-to-use-in-tests)
* [Documentation](#documentation)
* [API Gateway](#api-gateway)
* [SaaS Tools](#saas-tools)
* [Miscellaneous](#miscellaneous)

## Design

* [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist) ⭐ 23,170 | 🐛 1 | 📅 2026-02-10 - Best practices about REST API security
* [HTTP API design guide extracted from work on the Heroku Platform API](https://github.com/interagent/http-api-design) ⭐ 13,699 | 🐛 30 | 📅 2024-01-16
* [Architectural Styles and the Design of Network-based Software Architectures](https://roy.gbiv.com/pubs/dissertation/top.htm) - Roy Fielding's dissertation defining REST
* [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [How to design a REST API?](https://blog.octo.com/en/design-a-rest-api/) - Full guide tackling security, pagination, filtering, versioning, partial answers, CORS, etc.
* [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html) - Explained by Martin Fowler, originally presented by Leonard Richardson at the [QCon 2008](https://www.crummy.com/writing/speaking/2008-QCon/act3.html).
* [Enterprise Integration Using REST](https://martinfowler.com/articles/enterpriseREST.html) - Discusses the constraints and flexibility that you have with nonpublic APIs, and lessons learned from doing large scale RESTful integration across multiple teams.
* [HATEOAS](https://web.archive.org/web/20201111235328/timelessrepo.com/haters-gonna-hateoas) - Clear explanation on what HATEOAS is, and why you should use it.
* [How to GET a cup of coffee](https://www.infoq.com/articles/webber-rest-workflow/)
* [REST API Tutorial](https://www.restapitutorial.com/) - RestApiTutorial.com is dedicated to tracking REST API best practices and making resources available to enable quick reference and self education for the development crafts-person.

### Guidelines

* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md#readme) ⭐ 23,227 | 🐛 168 | 📅 2025-08-11 - The Microsoft REST API Guidelines, as a design principle, encourages application developers to have resources accessible to them via a RESTful HTTP interface.
* [Restful API Guidelines by Zalando](https://github.com/zalando/restful-api-guidelines) ⭐ 3,145 | 🐛 16 | 🌐 CSS | 📅 2026-01-06 - Developing Restful APIs: A Comprehensive Set of Guidelines.
* [Adidas REST API Guidelines](https://github.com/adidas/api-guidelines/blob/master/rest-api-guidelines/rest.md) ⭐ 398 | 🐛 0 | 📅 2025-09-19 - Adidas REST API Guidelines define standards and guidelines for building REST APIs at adidas.
* [Haufe API Style Guide](https://github.com/Haufe-Lexware/api-style-guide) ⭐ 243 | 🐛 21 | 📅 2023-07-20 - Guidelines created by Haufe-Lexware CTO team.
* [Cisco REST API Guide](https://github.com/CiscoDevNet/api-design-guide) ⭐ 119 | 🐛 1 | 📅 2024-01-11 - Guidelines for designing REST APIs at Cisco.
* [Atlassian REST API design guidelines version 1](https://developer.atlassian.com/server/framework/atlassian-sdk/atlassian-rest-api-design-guidelines-version-1/) - This document provides guidelines to Atlassian developers who are designing REST APIs for Atlassian applications.
* [Google Cloud API design guide](https://cloud.google.com/apis/design/) - Guidelines Google follows when designing Cloud APIs and other Google APIs (REST APIs and gRPC APIs).

## Standards

* [JSON API](https://jsonapi.org/) - Standard for building APIs in JSON.
* [RAML](https://raml.org/) - Simple and succinct way to describe RESTful API.
* [JSend](https://github.com/omniti-labs/jsend) ⭐ 1,705 | 🐛 9 | 📅 2022-01-21 - Simple specification that lays down some rules for how JSON responses from web servers should be formatted.
* [OData](https://www.odata.org/) - Open protocol to allow the creation and consumption of queryable and interoperable RESTful APIs. Quite complex.
* [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-06) - Simple format that gives a consistent and easy way to hyperlink between resources in your API.
* [JSON-LD](https://json-ld.org/) - Standard for describing Linked Data and hypermedia relations in JSON (W3C).
* [Hydra](https://www.hydra-cg.com/) - Vocabulary for Hypermedia-Driven Web APIs (W3C).
* [Schema.org](https://schema.org) - Collection of schemas describing common data models.
* [OpenAPI](https://openapis.org/) - Formerly known as the Swagger Specification, OpenAPI specifcation is the world’s most popular description format for defining Restful APIs.

## Clients

### PHP Clients

* [Buzz](https://github.com/kriswallsmith/buzz) ⭐ 1,925 | 🐛 11 | 🌐 PHP | 📅 2025-07-07 - Another lightweight HTTP client.
* [unirest for PHP](https://github.com/Mashape/unirest-php) ⭐ 1,281 | 🐛 41 | 🌐 PHP | 📅 2025-04-14 - Simplified, lightweight HTTP client library.
* [Guzzle](https://guzzle.readthedocs.org/en/latest/) - HTTP client and framework for consuming RESTful web services.

### JavaScript Clients

* [restangular](https://github.com/mgonto/restangular) ⭐ 7,819 | 🐛 254 | 🌐 JavaScript | 📅 2020-10-05 - AngularJS service to handle REST API properly and easily.
* [restful.js](https://github.com/marmelab/restful.js) ⚠️ Archived - JS client for interacting with server-side RESTful resources.
* [traverson](https://github.com/basti1302/traverson) ⭐ 461 | 🐛 28 | 🌐 JavaScript | 📅 2026-02-03 - A Hypermedia API/HATEOAS Client for Node.js and the Browser
* [raml-client-generator](https://github.com/mulesoft/raml-client-generator) ⚠️ Archived - Generates static client libs for js.

### Node.js Clients

* [restler](https://github.com/danwrong/restler) ⭐ 1,984 | 🐛 103 | 🌐 JavaScript | 📅 2019-07-10 - REST client library for node.js.
* [unirest for Node.js](https://github.com/Mashape/unirest-nodejs) ⭐ 958 | 🐛 43 | 🌐 JavaScript | 📅 2025-04-14 - Simplified, lightweight HTTP client library.

### Ruby Clients

* [httparty](https://github.com/jnunemaker/httparty) ⭐ 5,897 | 🐛 43 | 🌐 Ruby | 📅 2026-01-14 - Makes HTTP fun again!
* [RESTClient](https://github.com/rest-client/rest-client) ⭐ 5,230 | 🐛 139 | 🌐 Ruby | 📅 2024-05-19 - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [excon](https://github.com/excon/excon) ⭐ 1,172 | 🐛 22 | 🌐 Ruby | 📅 2026-02-03 - Usable, fast, simple Ruby HTTP 1.1. It works great as a general HTTP(s) client and is particularly well suited to usage in API clients.
* [Spyke](https://github.com/balvig/spyke) ⭐ 906 | 🐛 17 | 🌐 Ruby | 📅 2025-11-04 - Interact with REST services in an ActiveRecord-like manner.
* [raml-ruby-client-generator](https://github.com/zlx/raml-ruby-client-generator) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2016-02-24 - Auto generate API client from a RAML file.
* [Net::HTTP](https://ruby-doc.org/3.2.0/stdlibs/net/Net/HTTP.html) - Net::HTTP provides a rich library which can be used to build HTTP user-agents.

### Go Clients

* [resty](https://github.com/go-resty/resty) ⭐ 11,526 | 🐛 9 | 🌐 Go | 📅 2026-02-01 - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [gopencils](https://github.com/bndr/gopencils) ⭐ 453 | 🐛 7 | 🌐 Go | 📅 2019-02-18 - Small and simple package to easily consume REST APIs.

### .NET Clients

* [RestSharp](https://github.com/restsharp/RestSharp) ⭐ 9,826 | 🐛 36 | 🌐 C# | 📅 2026-02-06 - Simple REST and HTTP API client for .NET
* [Refit](https://github.com/reactiveui/refit) ⭐ 9,393 | 🐛 201 | 🌐 C# | 📅 2026-02-09 - The automatic type-safe REST library for Xamarin and .NET
* [RestEase](https://github.com/canton7/RestEase) ⭐ 1,110 | 🐛 15 | 🌐 C# | 📅 2023-12-10 - Easy-to-use typesafe REST API client library, which is simple and customisable. Heavily inspired by Refit
* [Tiny.RestClient](https://github.com/jgiacomini/Tiny.RestClient) ⭐ 209 | 🐛 18 | 🌐 C# | 📅 2026-02-02 - Simpliest Fluent REST client for .NET.
* [Apizr](https://github.com/Respawnsive/Apizr) ⭐ 172 | 🐛 4 | 🌐 C# | 📅 2025-04-16 - Refit-based web api client, but resilient (retry, connectivity, cache, auth, log, priority, etc...).
* [RestLess](https://github.com/letsar/RestLess) ⭐ 113 | 🐛 8 | 🌐 C# | 📅 2022-12-07 - The automatic type-safe-reflectionless REST API client library for .Net Standard.
* [Flurl](https://flurl.dev) - Fluent, portable, testable REST/HTTP client library

### Generators

* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) ⭐ 25,790 | 🐛 5,581 | 🌐 Java | 📅 2026-02-10 - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3).

## Servers

### Directly On Top Of A RMDB

* [postgrest](https://github.com/begriffs/postgrest) ⭐ 26,495 | 🐛 378 | 🌐 Haskell | 📅 2026-02-08 - Serve a fully RESTful API directly from an existing PostgreSQL database.
* [pREST](https://github.com/prest/prest) ⭐ 4,519 | 🐛 147 | 🌐 Go | 📅 2026-02-09 - A fully RESTful API from any existing PostgreSQL database written in Go.
* [MySQL HTTP plugin](http://blog.ulf-wendel.de/2014/mysql-5-7-http-plugin-mysql/) - Simple REST-like / CRUD server for any MySQL database.

### Node.js

* [node-restify](https://github.com/restify/node-restify) ⭐ 10,720 | 🐛 130 | 🌐 JavaScript | 📅 2024-09-19 - Framework specifically meant for REST API.
* [Nestjsx/crud](https://github.com/nestjsx/crud) ⭐ 4,324 | 🐛 292 | 🌐 TypeScript | 📅 2024-07-16 - Generate CRUD controllers and services for RESTful API with NestJS and TypeORM.
* [rest-hapi](https://github.com/JKHeadley/rest-hapi) ⭐ 1,186 | 🐛 76 | 🌐 JavaScript | 📅 2023-03-26 - Generate RESTful API based on mongoose models that supports relational data.
* [Expressa](https://github.com/thomas4019/expressa) ⭐ 449 | 🐛 22 | 🌐 JavaScript | 📅 2026-01-22 - Express middleware for creating APIs from JSON schemas with a simple admin editor and permissions model.
* [flatiron/resourceful](https://github.com/flatiron/resourceful) ⭐ 355 | 🐛 38 | 🌐 JavaScript | 📅 2015-01-12 - Isomorphic Resource engine for JavaScript.
* [mers](https://github.com/jspears/mers) ⭐ 343 | 🐛 14 | 🌐 JavaScript | 📅 2015-06-21 - Express service exposing Mongoose finders as RESTful API.
* [Sails.js](https://sailsjs.org/) - Node.js Web framework embedding a command to generate automatically a REST API.
* [loopback](https://loopback.io/) - Powerful Node.js framework for creating APIs and easily connecting to backend data sources.
* [Feathers](https://feathersjs.com/) - is a real-time, micro-service web framework that gives you control over your data via RESTful resources, sockets and flexible plug-ins.

### PHP

* [Fusio](https://github.com/apioo/fusio) ⭐ 2,069 | 🐛 172 | 🌐 PHP | 📅 2026-02-07 - Open source API management platform.
* [Negotiation](https://github.com/willdurand/Negotiation) ⭐ 1,423 | 🐛 11 | 🌐 PHP | 📅 2023-08-03 - Content negotiation library.
* [Restler](https://github.com/Luracast/Restler) ⭐ 1,372 | 🐛 35 | 🌐 PHP | 📅 2025-12-02 - Lightweight framework to expose PHP methods as RESTful web API.
* [Hateoas](https://github.com/willdurand/Hateoas) ⭐ 1,045 | 🐛 33 | 🌐 PHP | 📅 2026-01-10 - PHP library to support implementing representations for HATEOAS REST web services.
* [Apigility](https://github.com/zfcampus/zf-apigility-skeleton) ⚠️ Archived - API builder built with Zend Framework 2.
* [phprest](https://github.com/phprest/phprest) ⭐ 304 | 🐛 1 | 🌐 PHP | 📅 2020-07-28 - Specialized REST microframework for PHP.
* [HAL](https://github.com/blongden/hal) ⭐ 201 | 🐛 2 | 🌐 PHP | 📅 2026-01-05 - Hypertext Application Language (HAL) builder library.
* [Microrest](https://github.com/marmelab/microrest.php) ⚠️ Archived - Micro-web application providing a REST API on top of any relational database.
* [Drest](https://github.com/leedavis81/drest) ⭐ 87 | 🐛 3 | 🌐 PHP | 📅 2017-05-11 - Library for exposing Doctrine entities as REST resource endpoints.

#### Symfony2

* [API Platform](https://github.com/api-platform/api-platform) ⭐ 9,106 | 🐛 719 | 🌐 TypeScript | 📅 2026-02-04 - Specialize Symfony edition for the creation of hypermedia REST APIs.
* [FOSRestBundle](https://github.com/FriendsOfSymfony/FOSRestBundle) ⭐ 2,803 | 🐛 157 | 🌐 PHP | 📅 2026-02-10 - Bundle handling view, routing, error handling, etc. for your REST API.
* [DunglasApiBundle](https://github.com/dunglas/DunglasApiBundle) ⭐ 2,551 | 🐛 199 | 🌐 PHP | 📅 2026-02-10 - Build a REST API which follow Hydra/JSON-LD specification.
* [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) ⭐ 2,333 | 🐛 92 | 🌐 PHP | 📅 2026-02-04 - Generate documentation for your REST API from annotations.
* [Symfony REST Edition](https://github.com/gimler/symfony-rest-edition) ⚠️ Archived - Start with a Symfony2 application with all REST-friendly bundles pre-configured.
* [BazingaHateoasBundle](https://github.com/willdurand/BazingaHateoasBundle) ⭐ 296 | 🐛 11 | 🌐 PHP | 📅 2025-12-22 - Integrate the [Hateoas](https://github.com/willdurand/Hateoas) ⭐ 1,045 | 🐛 33 | 🌐 PHP | 📅 2026-01-10 library into a Symfony2 application.
* [stanlemon/rest-bundle](https://github.com/stanlemon/rest-bundle) ⚠️ Archived - Build a REST API based on Doctrine entities using conventions over configuration.
* [NgAdminGeneratorBundle](https://github.com/marmelab/NgAdminGeneratorBundle) ⚠️ Archived - Boostrap ng-admin configuration based on `stanlemon/rest-bundle`.
* [REST APIs with Symfony2: the Right Way](https://williamdurand.fr/2012/08/02/rest-apis-with-symfony2-the-right-way/) - Complete guide to build a state-of-the-art REST API with Symfony2 framework.

### PowerShell

* [Pode](https://github.com/Badgerati/Pode) ⭐ 1,022 | 🐛 109 | 🌐 PowerShell | 📅 2026-02-04 - Pode is an cross-platform, open-source, community-supported web server and REST API framework for PowerShell developers

### Python

* [FastAPI](https://github.com/tiangolo/fastapi) ⭐ 94,993 | 🐛 158 | 🌐 Python | 📅 2026-02-11 - FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. With automatic API documentation using Swagger UI and ReDoc, based on OpenAPI and JSON Schema.
* [Falcon](https://github.com/falconry/falcon) ⭐ 9,800 | 🐛 163 | 🌐 Python | 📅 2026-01-25 - Falcon is a bare-metal Python web API framework for building high-performance microservices, app backends, and higher-level frameworks.
* [apistar](https://github.com/encode/apistar) ⚠️ Archived - A smart Web API framework, designed for Python 3.
* [sandman](https://github.com/jeffknupp/sandman) ⭐ 2,297 | 🐛 37 | 🌐 Python | 📅 2021-12-25 - Automated REST APIs for existing database-driven systems.
* [Flask-Potion](https://github.com/biosustain/potion) ⚠️ Archived - Flask-Potion is a powerful Flask extension for building RESTful JSON APIs. It also provides several Clients for easier access to the API.
* [Django REST framework](https://www.django-rest-framework.org/) - Powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* [flask-restful](https://flask-restful.readthedocs.org/) - Extension for Flask that adds support for quickly building REST APIs.
* [flask-restless](https://flask-restless.readthedocs.org/en/latest/) - Flask extension for generating ReSTful APIs for database models defined with SQLAlchemy (or Flask-SQLAlchemy).
* [restless](https://restless.readthedocs.org/en/latest/) - Framework agnostic REST framework based on lessons learned from TastyPie.
* [Python Eve](https://python-eve.org/) - Eve is an open source Python REST API framework designed for human beings. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services.
* [Ramses](https://ramses.readthedocs.org/en/stable/) - Makes RAML files executable by generating production-ready APIs from them at runtime.
* [Zato](https://zato.io) - Platform for building server-side integrations, automations and API backends in Python.

### Ruby

* [Grape](https://www.ruby-grape.org) - Opinionated micro-framework for creating REST-like APIs in Ruby.
* [Rails](https://guides.rubyonrails.org/api_app.html) - RailsGuides: Using Rails for API-only applications.

### Go

* [go-restful](https://github.com/emicklei/go-restful) ⭐ 5,113 | 🐛 3 | 🌐 Go | 📅 2025-12-15 - A declarative highly readable framework for building restful API's.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) ⭐ 3,502 | 🐛 45 | 🌐 Go | 📅 2021-01-23 - Thin layer on top of `net/http` that helps building RESTful APIs easily.
* [sleepy](https://github.com/dougblack/sleepy) ⭐ 670 | 🐛 10 | 🌐 Go | 📅 2017-11-26 - RESTful micro-framework written in Go.
* [gocrud](https://github.com/manishrjain/gocrud) ⭐ 306 | 🐛 7 | 🌐 Go | 📅 2019-03-01: Go library to simplify creating, updating and deleting arbitrary depth structured data — to make building REST services fast and easy.
* [go-relax](https://github.com/codehack/go-relax) ⭐ 154 | 🐛 0 | 🌐 Go | 📅 2025-11-02 - Framework of pluggable components to build RESTful API's.
* [go-rest](https://github.com/ungerik/go-rest) ⭐ 128 | 🐛 2 | 🌐 Go | 📅 2017-01-20 - Small and evil REST framework for Go.
* [restit](https://github.com/yookoala/restit) ⭐ 55 | 🐛 6 | 🌐 Go | 📅 2025-04-16 - Go micro framework to help writing RESTful API integration test.
* [Resoursea](https://github.com/resoursea/api) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2015-02-01 - REST framework for quickly writing resource based services.

### Java

* [Dropwizard](https://github.com/dropwizard/dropwizard) ⭐ 8,594 | 🐛 34 | 🌐 Java | 📅 2026-02-11 - A framework for developing ops-friendly, high-performance, RESTful web services.
* [Vertx-Web](https://github.com/vert-x3/vertx-web) ⭐ 1,144 | 🐛 146 | 🌐 Java | 📅 2026-02-05 - Vert.x-Web is a set of building blocks for building web applications with Vert.x, a toolkit for building reactive applications on the JVM.
* [RestExpress](https://github.com/RestExpress/RestExpress) ⭐ 940 | 🐛 28 | 🌐 Java | 📅 2026-01-20 - Netty-based, highly performant, lightweight, container-less, plugin-extensible, framework that is ideal for microservice architectures.

### Scala

* [Chaos](https://github.com/mesosphere/chaos) ⚠️ Archived - A lightweight framework for writing REST services in Scala.

### Haskell

* [Rest for Haskell](https://github.com/silkapp/rest) ⭐ 386 | 🐛 50 | 🌐 Haskell | 📅 2018-10-02 - This package allows you to create REST APIs in Haskell. These APIs can be run in different web frameworks. They can also be used to automatically generate documentation as well as client libraries.

## Testing

### Querying

* [Insomnia](https://github.com/getinsomnia/insomnia) ⭐ 37,932 | 🐛 817 | 🌐 TypeScript | 📅 2026-02-11 - Cross-platform HTTP and GraphQL Client
* [httpie](https://github.com/jkbrzt/httpie) ⭐ 37,527 | 🐛 241 | 🌐 Python | 📅 2024-12-17 - Command line HTTP client, far more dev-friendly than `curl`.
* [jq](https://github.com/stedolan/jq) ⭐ 33,514 | 🐛 452 | 🌐 C | 📅 2026-02-01 - Command line JSON processor, to use in combination with a command-line HTTP client like cURL.
* [HTTP Prompt](https://github.com/eliangcs/http-prompt) ⭐ 9,102 | 🐛 53 | 🌐 Python | 📅 2024-05-21 - HTTP Prompt is an interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt\_toolkit.
* [rest-assured](https://github.com/rest-assured/rest-assured) ⭐ 7,109 | 🐛 585 | 🌐 Java | 📅 2026-02-04 - Java DSL for easy testing of REST services.
* [Schemathesis](https://github.com/schemathesis/schemathesis) ⭐ 3,037 | 🐛 39 | 🌐 Python | 📅 2026-02-10 - Property-based testing tool for web applications built with Open API and GraphQL specifications.
* [resty](https://github.com/micha/resty) ⭐ 2,654 | 🐛 17 | 🌐 Shell | 📅 2023-02-17 - Little command line REST client that you can use in pipelines (bash or zsh).
* [Step CI](https://github.com/stepci/stepci) ⭐ 1,835 | 🐛 70 | 🌐 TypeScript | 📅 2024-08-03 - Open-source framework for API Quality Assurance, which tests REST, GraphQL and gRPC automated and from Open API spec.
* [Http-console](https://github.com/cloudhead/http-console) ⭐ 1,475 | 🐛 14 | 🌐 JavaScript | 📅 2021-06-07 - Command line interface for HTTP that let you *speak HTTP like a local*
* [Milkman](https://github.com/warmuuh/milkman) ⭐ 1,324 | 🐛 15 | 🌐 Java | 📅 2025-12-18 - Extensible cross-platform request/response workbench, not only for http calls.
* [RestQA](https://github.com/restqa/restqa) ⭐ 93 | 🐛 18 | 🌐 JavaScript | 📅 2024-09-13 - A REST API testing Framework based on BDD / Gherkin to manage microservice local testing.
* [HttpMaster](https://www.httpmaster.net) - GUI tool for testing REST APIs and services. Windows OS only.
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) - Make HTTP requests with a simple web-based HTTP client.
* [TestMace](https://testmace.com) - Cross-platform simple but powerful IDE for API automation testing.

### Mocking

* [json-server](https://github.com/typicode/json-server) ⭐ 75,636 | 🐛 707 | 🌐 JavaScript | 📅 2026-02-11 - Serve a REST API from fixture files using quick prototyping.
* [DuckRails](https://github.com/iridakos/duckrails) ⚠️ Archived - Mock quickly & dynamically API endpoints.
* [FakeRest](https://github.com/marmelab/FakeRest) ⭐ 451 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-22 - Redirect fetch() calls to a client-side fake REST API.
* [Request Baskets](https://github.com/darklynx/request-baskets) ⭐ 418 | 🐛 21 | 🌐 Go | 📅 2024-06-27 - Service to collect HTTP requests and inspect them via RESTful API or web UI.
* [RequestBin](https://requestbin.com/) - Inspect and debug webhook requests sent by your clients or third-party APIs.
* [httpbin](https://httpbin.org) - HTTP request and response service - a/k/a Swiss Army Knife for HTTP.
* [MockServer](https://www.mock-server.com/) - Easy mocking of any system you integrate with via HTTP or HTTPS.
* [Mockoon](https://mockoon.com) - Easily create mock APIs locally. No remote deployment, no account required, open source.
* [Mockintosh](https://mockintosh.io/) - A mock server generator that's capable to generate RESTful APIs and communicate with the message queues to mimick asynchronous tasks.
* [Mockae](https://mockae.com/) - Fake REST API powered by Lua.

### Validating

* [JSON Schema](http://json-schema.org/) - Declarative language that allows you to annotate and validate JSON documents

### Public REST APIs To Use In Tests

* [Public APIS](https://github.com/public-apis/public-apis) ⭐ 397,726 | 🐛 832 | 🌐 Python | 📅 2025-11-04 - Explore The Largest API Directory In The Galaxy.
* [APIs.guru](https://APIs.guru) - Wikipedia for Web APIs, each API has OpenAPI/Swagger description.
* [JSON Placeholder](https://jsonplaceholder.typicode.com/) - Fake REST API abput posts, users and comments

## Documentation

* [Slate](https://github.com/lord/slate) ⚠️ Archived - Beautiful and responsive three-panel API documentation using Middleman.
* [ReDoc](https://github.com/Rebilly/ReDoc/) ⭐ 25,487 | 🐛 428 | 🌐 TypeScript | 📅 2026-02-07 - OpenAPI/Swagger-powered three-panel documentation.
* [Optic](https://github.com/opticdev/optic) ⚠️ Archived - Maintain an accurate API specification without writing OpenAPI/Swagger. Works with any Stack
* [raml2html](https://github.com/raml2html/raml2html) ⭐ 1,135 | 🐛 27 | 🌐 JavaScript | 📅 2022-09-22 - Generates HTML documentation from a RAML file.
* [Swagger](https://swagger.io/) - Documentation/querying web interface for REST APIs.
* [API doc](https://apidocjs.com/) - Inline Documentation for RESTful web APIs.
* [Zudoku](https://zudoku.dev/) - Create clean, consistent API docs with Zudoku — open source, extensible, and developer-first

## API Gateway

* [Kong](https://github.com/Kong/kong) ⭐ 42,729 | 🐛 131 | 🌐 Lua | 📅 2026-01-19 - Scalable, distributed, and plugin oriented API gateway backed by Nginx.
* [Tyk API Gateway](https://github.com/TykTechnologies/tyk) ⭐ 10,627 | 🐛 393 | 🌐 Go | 📅 2026-02-11 - Lightweight API gateway with analytics logging, written in Go.
* [KrakenD](https://github.com/devopsfaith/krakend) ⭐ 6,731 | 🐛 7 | 🌐 Go | 📅 2026-02-10 - Ultra performant API Gateway with middleware. Written in Go.
* [Express Gateway](https://github.com/ExpressGateway/express-gateway) ⭐ 3,035 | 🐛 78 | 🌐 JavaScript | 📅 2024-05-14 - Microservices API Gateway built on top of ExpressJS (Node.js).
* [API Umbrella](https://github.com/NREL/api-umbrella) ⭐ 2,145 | 🐛 243 | 🌐 Ruby | 📅 2026-02-10 - API management platform for exposing web services, with web interface and analytics, written in Lua.
* [WSO2 API Management](https://github.com/wso2/product-apim) ⭐ 965 | 🐛 655 | 🌐 Java | 📅 2026-02-03 - API management tool with lightweight gateway and API lifecycle management, written in Java.
* [AWS API Gateway](https://aws.amazon.com/api-gateway/) - Fully managed service that helps developers to create, publish, maintain, monitor, and secure APIs at any scale.
* [Zuplo](https://zuplo.com/) - OpenAPI-Powered API & MCP Management platform for Security, Deployment, and Documentation. Add auth, rate-limiting, and monetization to your API or MCP Server in minutes, written in TypeScript & Go.

## SaaS Tools

* [Nango](https://github.com/NangoHQ/nango) ⭐ 6,578 | 🐛 49 | 🌐 TypeScript | 📅 2026-02-10 - Native integrations framework to consume REST APIs (open-source).
* [Runscope](https://www.runscope.com/) - Automated API Monitoring & Testing.
* [Ping-API](https://ping-api.com/) - Automated API Monitoring & Testing.
* [Apiary](https://apiary.io/) - Collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing.
* [Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
* [Apigee](https://apigee.com) - Apigee is the leading provider of API technology and services for enterprises and developers.
* [3scale](https://www.3scale.net/) - Nginx based API gateway to integrate internal and external API services with 3scale's API Management Platform.
* [Assertible](https://assertible.com) - Continuously test and monitor your APIs after deployments and across environments.
* [Moesif](https://www.moesif.com) - API Analytics for Debugging, Monitoring, and Usage Tracking for RESTful and GraphQL.
* [Beeceptor](https://beeceptor.com/) - An HTTP inspecting, mocking and proxing service. Gives named endpoints for creating mock API endpoints and simulate responses.
* [Apitally](https://apitally.io) - Analytics, request logging and monitoring for REST APIs with a focus on simplicity and data privacy.

## Miscellaneous

* [react-admin](https://github.com/marmelab/react-admin) ⭐ 26,524 | 🐛 71 | 🌐 TypeScript | 📅 2026-02-10 - Add a ReactJS admin GUI to any RESTful API.
* [swagger-codegen](https://github.com/swagger-api/swagger-codegen) ⭐ 17,698 | 🐛 3,440 | 🌐 Mustache | 📅 2026-02-05 - Auto generation of client libraries or server stubs given an OpenAPI specification (formerly known as the Swagger Specification).
* [ng-admin](https://github.com/marmelab/ng-admin) ⭐ 3,921 | 🐛 111 | 🌐 JavaScript | 📅 2020-06-01 - Add an AngularJS admin GUI to any RESTful API.
* [shadcn-admin-kit](https://github.com/marmelab/shadcn-admin-kit) ⭐ 737 | 🐛 10 | 🌐 TypeScript | 📅 2026-02-10 - Build internal tools, admin panels, B2B apps, and dashboards on top of any REST API
* [Linx](https://linx.software) - Low-code API platform. Build, debug and host REST APIs

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](origin/httsp:/creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
