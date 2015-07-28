# Nuxeo Diff Pictures

## About

This project allows to build the Marketplace package for the `nuxeo-diff-pictures` module of the
[nuxeo-diff](https://github.com/nuxeo/nuxeo-diff/) addon.

It depends on the `nuxeo-diff` and `nuxeo-dam` marketplace packages.

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## Installing

To install the package:

 1. Take a fresh Nuxeo CAP (>= 7.3).

 2. Install the nuxeo-diff-pictures package:
      - From the AdminCenter (Upload + install)
      - From the command line using `nuxeoctl mp-install nuxeo-diff-pictures-$VERSION.zip`
