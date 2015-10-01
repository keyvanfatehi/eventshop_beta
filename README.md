eventshop_beta
==============

EventShop Documentation http://goo.gl/VyqFKK

_FIXME Continue to port the documentation from google docs to github markdown, refreshing it in the process_

# Introduction to EventShop

Inspired by PhotoShop, which hides the complex image processing under simple operators, EventShop provides simple graphical user interface (for nontechnical users) including several common spatio-temporal analysis operators which users can interactively apply over their registered data streams and formulate appropriate queries. Then, based on the recognized situation, a suitable action can be taken that may save lives and/or preserve resources.

## Features

* integrate and process streaming data from heterogeneous data sources
* detect various real-world situations in real-time
* send out recommendation to individuals based on given circumstance

# Installing EventShop

## Prerequisites

* Linux
* [MySQL](http://www.mysql.com/)
* [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Protobuf](https://github.com/google/protobuf)
* [OpenCV](http://opencv.org/)

_FIXME Determine and document latest versions of dependencies_

### Database Schema and Example Data

Download mysql scripts

* dbeventshop_initail.sql (with some example data)
* dbeventshop_schema.sql (create database with schema only)

_FIXME Fix that dead link, find those files, add them to the repository, and link them here_

# Running EventShop

_FIXME Add proper docs for running the actual system, assuming dependencies are installed_
