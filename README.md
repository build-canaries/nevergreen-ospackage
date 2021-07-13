# This package is no longer maintained

As everyone just seems to use Docker nowadays. 

# Nevergreen OS Package

## What is Nevergreen?

For more info visit https://github.com/build-canaries/nevergreen

## How to use this repo

This repo uses the [Gradle Linux Packaging Plugin](https://github.com/nebula-plugins/gradle-ospackage-plugin) to build a 
deployable Nevergreen package to make running your own instance on a Linux distro easier.

This repo contains some sensible defaults so may be used without changes. Some simple settings can be overridden by 
creating a `gradle.properties` file, see the [Gradle docs](https://docs.gradle.org/current/userguide/build_environment.html) 
for more details about placing this file in the correct place. 

Alternatively if you need to make more involved changes you can fork this repo and just use it as a base.

### Standalone Jar

The jar to package is downloaded automatically and placed into `build/libs` unless a file named `nevergreen-standalone.jar` 
already exists. This allows you to manually download or build your own jar locally.

### Overridable Properties

- `nevergreenVersion`
  The version of Nevergreen to download, e.g. 3.0.0

## Docker Image

Nevergreen is also available on [Dockerhub](https://registry.hub.docker.com/u/buildcanariesteam/nevergreen/).

## License

Copyright © 2014 - 2018 Build Canaries

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
