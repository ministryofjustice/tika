Apache Tika Server in Docker

Sets up a container based on
[dockerfile/java](https://registry.hub.docker.com/u/dockerfile/java/)

## Includes

  * [Apache Tika 1.6 Server](http://wiki.apache.org/tika/TikaJAXRS)

## Usage

To run the container, do the following:

    docker run -d -p 9998:9998 ministryofjustice/tika

    See the [Apache Tika 1.6 Server documentation ](http://wiki.apache.org/tika/TikaJAXRS) for other uses and usage examples.

## Building

To build the image, invoke:

    docker build github.com/ministryofjustice/tika

## Author

  * Todd Tyree (<tatyree@gmail.com>)

## Credits

  * Inspired by Andreas Wålm's (<andreas@walm.net>) [tika app
    repo/container](https://github.com/walm/docker-tika)

