# Angular Velocity

Fork of Velocity with added 25w14craftmine April Fools snapshot support.
This patched version does not provide any packet conversion for connections, 
but it allows connections between 25w14craftmine clients and 25w14craftmine servers
within your network, if present.
For package-conversion functionality, to provide a seemless switching experience between
snapshot and non-snapshot servers in your network, please take a look at 
[ViaAprilFools](https://hangar.papermc.io/ViaVersion/ViaAprilFools) project -
a ViaVersion extension for handling notable snapshot versions).

## Goals

* A codebase that is easy to dive into and consistently follows best practices
  for Java projects as much as reasonably possible.
* High performance: handle thousands of players on one proxy.
* A new, refreshing API built from the ground up to be flexible and powerful
  whilst avoiding design mistakes and suboptimal designs from other proxies.
* First-class support for Paper, Sponge, Fabric and Forge. (Other implementations
  may work, but we make every endeavor to support these server implementations
  specifically.)
  
## Building

Velocity is built with [Gradle](https://gradle.org). We recommend using the
wrapper script (`./gradlew`) as our CI builds using it.

It is sufficient to run `./gradlew build` to run the full build cycle.

## Running

Once you've built Velocity, you can copy and run the `-all` JAR from
`proxy/build/libs`. Velocity will generate a default configuration file
and you can configure it from there.

Alternatively, you can get the proxy JAR from the releases page.
