![Wealthy Laughing Duck Logo](img/logo.png "Wealthy Laughing Duck Logo")

# Introduction

Wealthy Laughing Duck is in fact a simple logic model that can be adapted by
various applications and platforms. It's supposed to be a personal finance
managing system. All duck components are just implementations of this model,
e.g. web interface implemented with JavaScript, Java Thrift server / PHP
Thrift client, python RESTful API (consumed by JavaScript interface) and so on.

Most of duck components are in early development phase so far, but the aim is
to make them mature, stable systems that would rely on different technologies
used. Developers would clone and easily deploy github repositories and examine
the implementation to learn the technologies.

# Contribution

This is more than welcome :) The more contributions and group members there
are, the more the duck project will improve. If you wish to make some commits
to existing repositories - or even create your own repository that illustrates
a technology that's not present in the duck project yet - just contact the
@wealthy-laughing-duck.

# List of duck components

 * [the original project](https://github.com/wealthy-laughing-duck/wealthy-laughing-duck):

    * Java Thrift server
    * PHP Thrift client
    * JavaScript interface

 * [Backbone/Marionette interface](https://github.com/wealthy-laughing-duck/duck-interface)

# Standards

As each duck component relies on the same logic model, different systems should
be able to access the same resources, such as: databases, files, file formats,
api designs, etc. To ease components communication with each other, some
standards were introduced:

## Database

 * type: `mysql`
 * database user: `duck_user`
 * database name: `duck_database`
 * password: wXyqhWzlF0uO20j8
 * host: `localhost`

Duck components will connect the database according to above parameters by
default.

## Other standards (to be added)

Those will include: database schema, thrift definitions, JSON api design, file
formats.
