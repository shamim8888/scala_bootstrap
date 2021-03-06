# Scala Bootstrap (base / project skeleton)
 
[![Software License][ico-license]][link-license]
[![Build Status][ico-travis]][link-travis]
 
## Introduction 

This is a repository intended to serve as a starting point if you want to bootstrap a project in Scala.
 
It could be useful if you want to start from scratch a kata or a little exercise or project. The idea is that you don't have to worry about the boilerplate, just clone this repo and there you go:
* Latest versions of Scala, SBT and ScalaTest in order to practice with them
* Best practices applied:
  * [`README.md`][link-readme] (badges included)
  * [`LICENSE`][link-license]
  * [`build.sbt`][link-build-sbt]
  * [`scalastyle-config.xml`][link-scalastyle-config]
  * [`.gitignore`][link-gitignore]
  * [`.editorconfig`][link-editorconfig]
  * [`.travis.yml`][link-travis-yml]

## How To Start

1. Clone this repository `git clone https://github.com/CodelyTV/scala_bootstrap`.
2. Run [SBT](http://www.scala-sbt.org/) on the project directory `sbt`.
3. Run the [scalatests](http://www.scalatest.org/) with `t`.
4. Check the [scalastyle](http://www.scalastyle.org/) in the production code with `s` and use the `ts` command to check the test code style.
5. Start your project!

## Other programming languages

* [PHP](https://github.com/CodelyTV/php-bootstrap)
* [Scala](https://github.com/CodelyTV/scala_bootstrap)

## About

This hopefully helpful utility has been developed by [CodelyTV][link-author] and [contributors][link-contributors].

We'll try to maintain this project as simple as possible, but Pull Requests are welcomed!

## License

The MIT License (MIT). Please see [License File][link-license] for more information.

[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/CodelyTV/scala_bootstrap/master.svg?style=flat-square

[link-license]: LICENSE
[link-travis]: https://travis-ci.org/CodelyTV/scala_bootstrap
[link-readme]: README.md
[link-build-sbt]: build.sbt
[link-scalastyle-config]: scalastyle-config.xml
[link-gitignore]: .gitignore
[link-editorconfig]: .editorconfig    
[link-travis-yml]: .travis.yml           
[link-author]: https://github.com/CodelyTV
[link-contributors]: ../../contributors
