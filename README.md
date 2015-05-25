# Nevergreen OS Package

## What is Nevergreen?

Nevergreen is a build monitor with attitude. It is awesome for two reasons:

-	Your builds should always be green. Nevergreen understands this and only shows you jobs that have failed or are building.
-	Nevergreen uses HTML localStorage. So the config is stored in your web browser. You only need to run it once to host hundreds of different build monitors.

For more info visit https://github.com/build-canaries/nevergreen

## How to use this repo

This repo uses the [Gradle Linux Packaging Plugin](https://github.com/nebula-plugins/gradle-ospackage-plugin) to build a deployable Nevergreen package to make running your own instance easier.

This repo contains some sensible defaults so may be used without changes. Some simple settings can be overridden by creating a gradle.properties file, see the [Gradle docs](https://docs.gradle.org/current/userguide/build_environment.html) for more details about placing this file in the correct place. 

Alternatively if you need to make more involved changes you can fork this repo and just use it as a base.

### Overridable Properties

- `nevergreenVersion`
  The version of Nevergreen to download, e.g. 0.5.0

## Docker Image

Nevergreen is also available on Dockerhub. You can access it [here](https://registry.hub.docker.com/u/buildcanariesteam/nevergreen/).

## License

Copyright © 2015 Build Canaries

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.