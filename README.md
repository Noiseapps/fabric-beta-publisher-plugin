# fabric-beta-publisher
A Jenkins plugin that lets you publish Android apps to [Fabric Beta](https://docs.fabric.io/android/beta/overview.html).

## Features

* Upload APK file to Fabric Beta
* Choose to notify testers
  * By a group alias
  * By a list of e-mails
* Specify release notes
  * From the Jenkins changelog
  * With a build parameter
  * From a text file
* Pipeline support
* Add `FABRIC_BETA_BUILD_URL` and `FABRIC_BETA_BUILD_URL_{n}` environment variables after successful upload. The `{n}` is replaced with the APK index.

## Screenshot

<img width="600px" src="http://i.imgur.com/ladnLhk.png"/>
