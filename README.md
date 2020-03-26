# intellij-warden

This plugin provides support for the Warden orchestration tool in PhpStorm and IntelliJ

## Getting Started
Once stable, a public release will be made to the JetBrains Plugin Repository. For now you must install from one of
the Jar files that are on the [Releases](https://github.com/WileESpaghetti/intellij-warden/releases) page.

## Installing
To install:
* Download the [latest jar file](https://github.com/WileESpaghetti/intellij-warden/releases/download/v0.0.0.1/intellij-warden-1.0-0.jar)
* Open the Settings/Preferences dialog
* Select Plugins
* On the Plugins page, click The Settings button and then click Install Plugin from Disk.
* Select the plugin archive file and click OK.
* Click OK to apply the changes and restart the IDE

## Features
This project is still in the very early stages

### Current
* Adds the "Warden" module type that can be selected when you create a new project
* Runs `warden env-init` to bootstrap the project
    * currently hard codes environment settings
    
### Planned
* Allow selecting the  `magento1`, `magento2`, and `laraval` project types
* Allow Warden environment to be customized as part of the project creation process
* Integrate with the run configuration

## Building
`intellij-warden` uses the standard [Gradle build process](https://www.jetbrains.org/intellij/sdk/docs/tutorials/build_system/prerequisites.html).

## Reporting issues
Please report any issues on https://github.com/WileESpaghetti/intellij-warden/issues