# [scr-be] arthur-doctrine-behavior-bundle

| Continuous Integration |   Code Quality Review   |    UnitTest Coverage    |
|:----------------------:|:-----------------------:|:-----------------------:|
| [![Travis](https://scr.be/arthur-doctrine-behavior-bundle/travis_shield)](https://scr.be/arthur-doctrine-behavior-bundle/travis) | [![Codacy](https://scr.be/arthur-doctrine-behavior-bundle/codacy_shield)](https://scr.be/arthur-doctrine-behavior-bundle/codacy) | [![Coveralls](https://scr.be/arthur-doctrine-behavior-bundle/coveralls_shield)](https://scr.be/arthur-doctrine-behavior-bundle/coveralls) |

## Overview

[Welcome](https://scr.be/go/readme_welcome)!
The `scr-be/arthur-doctrine-behavior-bundle` package provides
a set of Doctrine subscribers to provide different behaviors, such as updated_on, create_on, published, etc.

### Grouping

This package is part of the [arthur](https://scr.be/arthur-doctrine-behavior-bundle/group)
group ([explanation](https://scr.be/arthur-doctrine-behavior-bundle/group_explanation)),
comprised of other releases with a concentration in 
*core doctrine base classes*,
and related functionality.

### JTT

This package represents a single project within a
[large collection](https://scr.be/go/explore) of open-source code released
under the *Scribe* namespace, comprised of framework-agnostic libraries,
and a number of Symfony bundles. These projects are authored and maintained
by [Rob Frawley 2nd](https://scr.be/rmf) and 
[collaborators](https://scr.be/arthur-doctrine-behavior-bundle/github_collaborators),
often with the support of [Scribe Inc](https://scr.be/go/scribe-home).

## Quick Start

### Installation

Get the code by requiring it explicitly via the [Composer](https://getcomposer.com)
CLI, or by editing your *composer.json* to reflect the dependency and updating
your project requirements. For example, to explicitly require this project using
the CLI, use the following command.

```bash
$ composer require scr-be/arthur-doctrine-behavior-bundle
```

To enable the bundle, register it with your Symfony application kernel by
instantiating *ScribeArthurDoctrineBehaviorBundle* within the bundle array.

```php
// app/AppKernel.php
class AppKernel extends Kernel {
    public function registerBundles() {
        $bundles = [
            // ...
            new Scribe\Arthur\DoctrineBehaviorBundle\ScribeArthurDoctrineBehaviorBundle(),
        ];
        // ...
    }
}
```

### Configuration

Available configuration values can be referenced by using the Symfony console command
`app/console` (assuming the Symfony full-stack framework and bundle registration).
Additionally, this bundle provides a bare console executable that can be invoked by calling
the following.

```bash
bin/arthur-doctrine-behavior config:dump-reference scribe_arthur_doctrine_behavior
```

## Reference

### API Docs

This package's API-documentation is available at [scr.be/arthur-doctrine-behavior-bundle/api](https://scr.be/arthur-doctrine-behavior-bundle/api),
(as well as linked below via the *Reference* badge found under the *Additional Links*
header). All API-reference is build against the *master* Git branch and updated
automatically on each Git push---api-reference for *specific releases* will
be provided once this package has matured.

> The entire API-reference website is auto-generated using a quick,
> reliable, and well-developed CLI tool called [Sami](https://scr.be/go/sami).
> It is rigerously and regularly tested through its use in large, complex projects,
> such as the [Symfony Full-Stack Framework](https://scr.be/go/symfony) 
> <see: [scr.be/go/api-ref-symfony](https://scr.be/go/symfony-api)>, as well
> as its use in smaller projects such
> [Twig](https://scr.be/go/sami-twig)
> <see: [scr.be/go/api-ref-twig](https://scr.be/go/twig-api)>.
> Reference Sami's [GitHub page](https://scr.be/go/sami) to learn how to use
> it with your own projects!

### Examples/Tutorials

Currently, there is no *"human-written"* documentation---outside of this README.
Pending package stability and available resources, a
[RTD (Read the Docs)](https://scr.be/go/rtd) page will be published with
additional information and tutorials, including real use-cases within the Symfony
Framework.

## Contributing

### Discussion

For general inquiries or to discuss a broad topic or idea, you can find
*robfrawley* on Freenode. There is also a *#scribe* channel, which can
be joined using the following link
[irc.choopa.net:6669/scribe](irc://irc.choopa.net:6669/scribe).

### Issues

To report issues or request a new feature use
[GitHub](https://scr.be/arthur-doctrine-behavior-bundle/github_issues)
or [GitLab](https://scr.be/arthur-doctrine-behavior-bundle/gitlab_issues)
to start a discussion. Include as much information as possible to aid in
a quick resolution. Feel free to "ping" the topic if you don't get a
response within a few days.

### Code

You created additional functionality during the use of this package? Send
it back upstream! *Don't hesitate to submit a pull request!* Beyond the
brief requirements outlined in the
[contibuting guide](https://scr.be/arthur-doctrine-behavior-bundle/contributing),
your [imagination](https://scr.be/go/readme_imagination)
represents the only limitation.

## License

This project is licensed under the
[MIT License](https://scr.be/go/mit), an
[FSF](https://scr.be/go/fsf)-/[OSI](https://scr.be/go/osi)-approved
and [GPL](https://scr.be/go/gpl)-compatible, permissive free software
license. Review the
[LICENSE](https://scr.be/arthur-doctrine-behavior-bundle/license)
file distributed with this source code for additional information.

## Additional Links

|       Purpose | Status        |
|--------------:|:--------------|
| *Stable Release*    | [![Packagist](https://scr.be/arthur-doctrine-behavior-bundle/packagist_shield)](https://scr.be/arthur-doctrine-behavior-bundle/packagist) |
| *Dev Release*    | [![Packagist](https://scr.be/arthur-doctrine-behavior-bundle/packagist_pre_shield)](https://scr.be/arthur-doctrine-behavior-bundle/packagist) |
| *License*    | [![License](https://scr.be/arthur-doctrine-behavior-bundle/license_shield)](https://scr.be/arthur-doctrine-behavior-bundle/license) |
| *Reference*  | [![License](https://scr.be/arthur-doctrine-behavior-bundle/api_shield)](https://scr.be/arthur-doctrine-behavior-bundle/api) |
