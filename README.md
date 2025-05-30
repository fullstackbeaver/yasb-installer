# Yajsb Installer
================

This project allows to start quickly a Yajsb project

## Table of Contents
-----------------

* [Getting Started](#getting-started)
* [Usage](#usage)
* [Scripts](#scripts)

## Getting Started
---------------

This project is a Yajsb installer, which uses Bun to manage dependencies and scripts.

## Usage
-----

To use the installer, run the following command in the folder you want to create your new project:

```bash
wget --no-cache https://raw.githubusercontent.com/fullstackbeaver/yajsb-installer/refs/heads/main/installer.js
bun installer.js
```

It's a little weird because YAjSB is not published yet and also this installer

## Scripts
--------

The project includes only a build script defined in the `package.json` file.

* `build`: Builds the installer using Bun.

```bash
bun run build
```
