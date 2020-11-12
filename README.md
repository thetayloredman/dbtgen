---
description: >-
  DBTGen, standing for "Discord Bot Generator" is a specification/program for
  DBTGen files and the generators that use them.
---

# Welcome to the DBTGen Documentation!

## What is DBTGen?

DBTGen stands for Discord Bot Generator.

DBTGen can mean 2 things:

* The DBTGen file standard that describes DBTGen configuration
* and DBTGen generators for making bots from those configurations

Let's go ever both of these in detail.

### The DBTGen file standard

DBTGen consists of 2 parts. For it to do its job, there first needs to be configuration files.

The configuration files usually are placed in a folder where all of the DBTGen related items go.

### DBTGen generators

DBTGen generators read the [configuration files](./#the-dbtgen-file-standard) and create full-fledged Discord bots from the input.

Most generators are designed for a single language. For example, the **Node.js DBTGen Generator** generates output files in **JavaScript** designed to run under the _Node.js_ runtime environment.

