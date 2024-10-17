# QUPAS-ARGOS
## 0. Content
  1. ArGoS Instalation
  2. 

## Prerequisites:
  1. Ros 1 Noetic.
  2. Ubuntu 20.04


## 1. ArGoS Instalation
https://www.argos-sim.info/download.php

```bash
sudo apt-get install cmake libfreeimage-dev libfreeimageplus-dev \
  qt5-default freeglut3-dev libxi-dev libxmu-dev liblua5.3-dev \
  lua5.3 doxygen graphviz libgraphviz-dev asciidoc
```



```bash
git clone https://github.com/ilpincy/argos3.git argos3
```


```bash
cd argos3
mkdir build_simulator
cd build_simulator
cmake ../src
make
```




