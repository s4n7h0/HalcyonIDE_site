---
date: 2018-01-10T23:39:17+01:00
title: Getting started
weight: 10
---

## Installation

### Installing Halcyon IDE

Halcyon IDE is developed in java to make it simpler to use in all possible operating systems. Running this cannot be more simpler. Download the jar file from [here](https://github.com/s4n7h0/Halcyon/releases/download/2.0.1/Halcyon_IDE_v2.0.1.jar) and run using command below.
```sh 
java -jar Halcyon_IDE_v2.0.1jar
```


### Installing from Source

You can also download the source from `git` and are free to compile the project in your own local machines. 

```sh
# install dependencies 
apt-get install default-jre
apt-get install ant

# clone from git
cd /opt
git clone https://github.com/s4n7h0/Halcyon.git

# compile the source 
cd Halcyon/
ant
java -cp /opt/Halcyon/src/lib/autocomplete.jar:/opt/Halcyon/src/lib/rsyntaxtextarea.jar:/opt/Halcyon/dist/Halcyon_IDE_v2.0.1.jar halcyon.ide.HalcyonIDE    

```


## Configuration

Halcyon IDE uses Nmap program files installed on the running machine. When running for the very first time, the IDE asks to configure this. Halcyon IDE configuration wizard can automatically identify nmap files and make this setting easier for you. You may need to restart Halcyon IDE for the settings to take affect.  

 
