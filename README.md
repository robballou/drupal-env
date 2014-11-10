# Drupal Env

Command line tool to build and rebuild Drupal environments.

**Note:** Currently this is a stub of an idea that I would like to work on.
Opinions, questions, and people to help flesh this out would be most excellent.

## Install

    npm install drupal-env

## Usage

    cd ~/some-project
    denv init
    denv up

## Providers

Drupal Env uses providers to let you use the virtualization tools you want to
use. If you want to use something new, you can write a new provider.

Current providers:

* Vagrant

Things I would also like to bundle:

* Docker

## Configuration

When initializing a new environment, a `.denv.yaml` file will be created with
default configuration, which is updated based on any arguments passed into the
`denv init` call.
