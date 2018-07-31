# Islandora Dimensions.ai

## Introduction

Provides a Dimensions.ai badge on objects, providing citation counts and links to more detailed pages showing articles that referenced the work. 
Applies to any object with a DOI, within selected content models. For use with Islandora Badges.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Islandora Badges](../../)

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Configuration path is admin/islandora/tools/badges/dimensions (Administration > Islandora > Islandora Utility Modules > Islandora Badges Configuration > Dimensions.ai).

There is one configurable option:

* Dimensions Badge
     * provide one of the [badge types](https://badge.dimensions.ai/?identifier=pub.1036867202#build) defined by Dimensions.ai. Default is the small rectangular badge. 

The module provides a block, Islandora Dimensions.ai, that can be placed in a block region.

Once enabled the badge is displayed on objects that have a DOI as configured and citations. If it has a DOI but does not display,  the article does not currently have any citations recorded by the Dimensions.ai service.

## Troubleshooting/Issues

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## Maintainers/Sponsors

Current maintainers:

* [Brandon Weigel](https://github.com/bondjimbond)

## Development

If you would like to contribute to this module, please check out [CONTRIBUTING.md](CONTRIBUTING.md). In addition, we have helpful [Documentation for Developers](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers) info, as well as our [Developers](http://islandora.ca/developers) section on the [Islandora.ca](http://islandora.ca) site.

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
