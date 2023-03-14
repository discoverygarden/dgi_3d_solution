# DGI 3D Solution

## Introduction
A Drupal module to handle 3D objects within the context of Islandora.
All related implementation details that can be cleanly decoupled from the context of Islandora
will be captured in separate modules and referenced here as needed.

## Requirements

This module requires the following modules/libraries:

* [Islandora Core Feature](https://github.com/Islandora/islandora), a submodule of Islandora
* [Migrate Plus](https://www.drupal.org/project/migrate_plus)
* The core Drupal taxonomy module

## Installation

Install as usual, see
[this](https://www.drupal.org/docs/extending-drupal/installing-modules) for
further information.

## Usage
Currently this only provides a Migration to adds a '3D Object' term to the 'Islandora Models' Taxonomy.
The migration can be imported as part of the 'islandora' migration group, or individually as needed.

## Troubleshooting/Issues

Having problems or solved one? contact
[discoverygarden](http://support.discoverygarden.ca).

## Maintainers
Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module create an issue, pull request
and or contact
[discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
