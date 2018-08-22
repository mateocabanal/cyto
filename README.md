# electroBUCKS
Electrobucks, a privacy focused cryptocurrency

Dependencies
-------------

Boost 1.55 or higher,
CMake,
gcc,

To install on debian or ubuntu,

```   
sudo apt install libboost-all-dev cmake make build-essential gcc g++ -y

```
Install/Compiling
------------------

To compile:
```
git clone https://github.com/oetam5002/electrobucks
cd electrobucks
make clean
rm -rf CMakeCache.txt && rm -rf CMakeFiles
cmake .
make -j8 && bash finish.sh
```
where 8 = number of threads

When done, run:
```
./electrobucksd --seed-node 108.172.131.200:18000
```

Help
-----------------

Any help would be appreciated
