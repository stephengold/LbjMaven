[The LbjMaven project][project] provides
a sample desktop application
for [the Libbulletjme physics library][lbj],
built using Maven and Java.

Complete source code is provided under
[a 3-clause BSD license][license].


## How to build and run LbjMaven from source

To build the project:

1. Install a [Java Development Kit (JDK)][adoptium],
   version 8 or higher,
   if you don't already have one.
2. Point the `JAVA_HOME` environment variable to your JDK installation:
   (In other words, set it to the path of a directory/folder
   containing a "bin" that contains a Java executable.
   That path might look something like
   "C:\Program Files\Eclipse Adoptium\jdk-21.0.12-hotspot"
   or "/usr/lib/jvm/jdk-21.0.12+8" or
   "/Library/Java/JavaVirtualMachines/zulu-21.jdk/Contents/Home" .)
  + using Bash or Zsh: `export JAVA_HOME="` *path to installation* `"`
  + using [Fish]: `set -g JAVA_HOME "` *path to installation* `"`
  + using Windows Command Prompt: `set JAVA_HOME="` *path to installation* `"`
  + using PowerShell: `$env:JAVA_HOME = '` *path to installation* `'`
3. Install [Maven], if you don't already have it.
4. Download and extract the LbjMaven source code from GitHub:
  + using [Git]: `git clone https://github.com/stephengold/LbjMaven`
5. `cd LbjMaven`
6. `mvn package`

To run the "HelloLibbulletjme" application:
  + `mvn exec:java`


[adoptium]: https://adoptium.net/temurin/releases/ "Adoptium Project"
[fish]: https://fishshell.com/ "Fish command-line shell"
[git]: https://git-scm.com "Git version-control system"
[lbj]: https://stephengold.github.io/Libbulletjme "Libbulletjme project"
[license]: https://github.com/stephengold/LbjMaven/blob/master/LICENSE "LbjMaven license"
[maven]: https://maven.apache.org/ "Maven Project"
[project]: https://github.com/stephengold/LbjMaven "LbjMaven project"
