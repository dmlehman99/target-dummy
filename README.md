# target-dummy

[![CircleCI](https://circleci.com/gh/dmlehman99/target-dummy/tree/master.svg?style=svg)](https://circleci.com/gh/dmlehman99/target-dummy/tree/master) [![Docker Pulls](https://img.shields.io/docker/pulls/mashape/kong.svg?maxAge=2592000)]()

Docker image bundled with DVNA [Damn Vulnerable Node Application] (https://github.com/quantumfoam/DVNA) and Gruyere [http://google-gruyere.appspot.com/](http://google-gruyere.appspot.com/).  Intended for using as a test target for security testing and pen test training.

###Usage

    docker run -d -p 3000:3000 -p 8008:8008 dmlehman/target-dummy
