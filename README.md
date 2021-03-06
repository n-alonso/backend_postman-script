# postman-script

## Problem Description

The Operations team was is able to delegate access to more than 1 bank at a time.
The API endpoint that performs this task only accepts 1 source application, 1 target application, and 1 bank.

## Goals

* Automate the process to require less manual work
* Speed up the process for delegations to be more time efficient
* Easy to perform task with minimal technical knowledge

## Description

This script allows for a Postman collection to run and repeat the same request over and over again, while iterating through 2 array:
* Applications Array
* Banks Array

The collection will run the request as many times as necessary while also implementing some basic error handling and will use only local collection variables (no environment) to minimise the previous Postman knowledge required.
