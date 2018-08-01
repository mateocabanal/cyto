# electroBUCKS
Electrobucks, a privacy focused cryptocurrency

Dependencies
-------------

Boost 1.55 or later,
CMake,
gcc,
tor

To install on debian or ubuntu,

```   
sudo apt install libboost-all-dev cmake make build-essential gcc g++ tor -y

```
Install/Compiling
------------------

To compile:

```git clone https://github.com/oetam5002/electrobucks
cd electrobucks
make clean
rm -rf CMakeCache.txt && rm -rf CMakeFiles
cmake .
make -j8 && bash finish.sh
```

where 8 = number of threads

Help
-----------------

Any help would be appreciated
