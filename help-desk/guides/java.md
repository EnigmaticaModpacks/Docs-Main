# Java

## Installing Java

Before you start, you will need to make sure you have the correct version of Java installed. One of the most common problems that people encounter when running a server is having 32-bit Java or having the incorrect version of Java for the given Minecraft version. All Enigmatica modpacks require 64-bit Java, and the specific version required is listed below.



### Windows

* Go to [Adoptium.net](https://adoptium.net).
* For **Minecraft 1.16** or earlier: Select **Temurin 8** (LTS) as the version.
* For **Minecraft 1.17** or later: Select **Temurin 17** (LTS) as the version.
* Select Latest release if you are downloading it from a 64-bit Windows computer.
* Otherwise, select Other platforms and change Operating System to Windows and Architecture to x64.

### Ubuntu or Debian Linux

* For **Minecraft 1.16** or earlier: Run this command from the command line: `sudo apt-get install openjdk-8-jre`.
* For **Minecraft 1.17** or later: Run this command from the command line: `sudo apt-get install openjdk-17-jre`.

Note that the package might have a different name depending on the version of the distribution you are running, so you should get familiar with the _apt_ command and how to manage packages on your system.

### Fedora, RHEL, or CentOS Linux

* For **Minecraft 1.16** or earlier: Run this command from the command line: `su -c "yum install java-1.8.0-openjdk"`
* For **Minecraft 1.17** or later: Run this command from the command line:&#x20;
  * `su -c "yum install java-1.17.0-openjdk"`

Note that the package might have a different name depending on the version of the distribution you are running, so you should get familiar with the _yum_ command and how to manage packages on your system.

### Mac

* Go to [Adoptium.net](https://adoptium.net).
* For **Minecraft 1.16** or earlier: Select **Temurin 8** (LTS) as the version.
* For **Minecraft 1.17** or later: Select **Temurin 17** (LTS) as the version.
* Select Latest release if you are downloading it from a 64-bit macOS computer.
* Otherwise, select Other platforms and change Operating System to macOS and Architecture to x64.
