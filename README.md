This is a plugin for QtCreator IDE to easily create new Tufão projects.

# LICENSE

This plugins is licensed under the LGPLv3. The license only restricts the plugin
itself. The data produced by the plugin is property of the plugin user.

# BUILD

This plugin uses the qmake build system and depends on Qt Source Code to be
compiled.

## ENVIRONMENT VARIABLES

Before compiling the plugin, you need to set the following environment
variables:

  * QTC_SOURCE: Must point to QtCreator source code.
  * QTC_BUILD: Must point to QtCreator build.

## Folder name

Since QtCreator 2.8, you need to name the folder containing the Tufão plugin as
`tufao` or build will fail.

## Compiling

To compile the plugin, run the commands as follow:

    $ qmake
    $ make

NOTE:
If you want to build the plugin into your user config directory, you should run
the qmake commands as follows:

    $ qmake USE_USER_DESTDIR=yes

# INSTALL

The installation process should occur after the build. If you want to package
the plugin, just copy the local installation.

# USAGE

Open the QtCreator and follow the steps:
File >> New File or Project >> Tufão

# ChangeLog

## 0.2.6

 * Compatibility with QtCreator 3.1.0beta1

## 0.2.5

 * Compatibility with QtCreator 3.0

## 0.2.3

 * Compatibility with QtCreator 2.8.x
