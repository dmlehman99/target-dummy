# target-dummy

[![CircleCI](https://img.shields.io/circleci/project/dmlehman99/target-dummy.svg?maxAge=2592000?style=plastic)]()
[![Docker Pulls](https://img.shields.io/docker/pulls/dmlehman/target-dummy.svg?maxAge=2592000?style=plastic)]()
[![license](https://img.shields.io/github/license/dmlehman99/target-dummy.svg?maxAge=2592000?style=plastic)]()

Docker image bundled with DVNA [Damn Vulnerable Node Application] (https://github.com/quantumfoam/DVNA) and Gruyere [http://google-gruyere.appspot.com/](http://google-gruyere.appspot.com/).  Intended for using as a test target for security testing and pen test training.

###Usage

    docker run -d -p 3000:3000 -p 8008:8008 dmlehman/target-dummy

###MIT license

Copyright (c) 2016, Matt Lehman
