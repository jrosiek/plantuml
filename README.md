PlantUML
========
[![Build Status](https://travis-ci.com/jrosiek/plantuml.svg?branch=dev)](https://travis-ci.com/jrosiek/plantuml)

Generate UML diagram from textual description

To know more about PlantUML, please visit http://plantuml.com/

This repository is a fork of the official PlantUML GitHub repository at [plantuml/plantuml](https://github.com/plantuml/plantuml). 
The changes you can find here are mostly about:

* Writing automated tests for various parts of the PlantUML
* Necessary code refactorings to make writing tests possible
* Bug fixes and minor functionality improvements
* Modernisation of the codebase
  * Java >=1.8
  * No more Ant as a build tool

You might have noticed many corner cases and
inconsistencies in the syntax and behaviour of the tool 
if you are a hardcore user of PlantUML as me. 
It's not that big surprise if you consider there are no automated tests 
in the original PlantUML source code (at least no publicly available tests). 
This fork is intended to make some improvements in this regard. 
It would be great to have it integrated into the official repo. 

I am more than happy to accept contributions if you are interested in this type of work.  

## Repository organisation

* `master` - default branch. It is supposed to be in sync with `dev` and contain updated README.md that you are just reading. 
* `dev` - here the work is integrated. Pull requests should be submitted against this repo. 
* _feature branches_

## Roadmap

### Planned

- [ ] Adding support for writing tests
- [ ] Tests for the first stage of processing (preprocessor).

### Backlog 

- Tests for diagram parsers
- Tests for diagram generators