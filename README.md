# *Quasar*<br/>Fibers, Channels and Actors for the JVM
[![Build Status](https://travis-ci.org/puniverse/quasar.svg?branch=master)](https://travis-ci.org/puniverse/quasar) [![Dependency Status](https://www.versioneye.com/user/projects/52b019baec1375ace70000de/badge.png?style=flat)](https://www.versioneye.com/user/projects/52b019baec1375ace70000de) [![Version](http://img.shields.io/badge/version-0.7.3-blue.svg?style=flat)](https://github.com/puniverse/quasar/releases) [![License](http://img.shields.io/badge/license-EPL-blue.svg?style=flat)](https://www.eclipse.org/legal/epl-v10.html) [![License](http://img.shields.io/badge/license-LGPL-blue.svg?style=flat)](https://www.gnu.org/licenses/lgpl.html)


## Getting started

Add the following Maven/Gradle dependencies:

| Feature          | Artifact
|------------------|------------------
| Core (required)  | `co.paralleluniverse:quasar-core:0.7.3[:jdk8]` (for JDK 8 optionally add the `jdk8` classifier)
| Actors           | `co.paralleluniverse:quasar-actors:0.7.3`
| Clustering       | `co.paralleluniverse:quasar-galaxy:0.7.3`
| Reactive Streams | `co.paralleluniverse:quasar-reactive-streams:0.7.3`
| Kotlin           | `co.paralleluniverse:quasar-kotlin:0.7.3`

Or, build from sources by running:

```
gradle install
```

## Usage

* [Documentation](http://docs.paralleluniverse.co/quasar/)
* [Javadoc](http://docs.paralleluniverse.co/quasar/javadoc)

You can also study the examples [here](https://github.com/puniverse/quasar/tree/master/quasar-actors/src/test/java/co/paralleluniverse/actors).

You can also read the introductory [blog post](http://blog.paralleluniverse.co/post/49445260575/quasar-pulsar).

When running code that uses Quasar, the instrumentation agent must be run by adding this to the `java` command line:

```
-javaagent:path-to-quasar-jar.jar
```

## Related Projects

* [Pulsar](https://github.com/puniverse/pulsar) is Quasar's extra-cool Clojure API
* [Comsat](https://github.com/puniverse/comsat) integrates Quasar with the JVM's web APIs

## Getting help

Questions and suggestions are welcome at this [forum/mailing list](https://groups.google.com/forum/?fromgroups#!forum/quasar-pulsar-user).

## License

Quasar is free software published under the following license:

```
Copyright (c) 2013-2015, Parallel Universe Software Co. All rights reserved.

This program and the accompanying materials are dual-licensed under
either the terms of the Eclipse Public License v1.0 as published by
the Eclipse Foundation

  or (per the licensee's choosing)

under the terms of the GNU Lesser General Public License version 3.0
as published by the Free Software Foundation.
```
