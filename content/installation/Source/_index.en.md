---
title: "Source"
date: 2018-12-29T11:02:05+06:00
weight: 2
draft: false
---

You can also download the source from git and free to compile the project in your own machines.

```bash
# install dependencies 
apt-get install default-jre
apt-get install ant

# clone from git
cd /opt
sudo git clone https://github.com/s4n7h0/Halcyon-IDE.git

# compile the source 
cd Halcyon-IDE/
ant -f build.xml package-for-store
java -cp /opt/Halcyon-IDE/src/lib/autocomplete.jar:/opt/Halcyon-IDE/src/lib/rsyntaxtextarea.jar:/opt/Halcyon-IDE/dist/Halcyon_IDE_vx.x.x.jar halcyon.ide.HalcyonIDE    
```


