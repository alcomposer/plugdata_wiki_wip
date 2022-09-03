

## Mac
PlugData requires an installation of Xcode, or at the very least the Xcode build tools.
If you have that installed, enter the following in the terminal:

### With Xcode
```
git clone --recursive https://github.com/timothyschoen/PlugData.git
cd PlugData
take build
cmake -G"XCode"
```
Then, either open the Xcode project or run ```cmake --build .```

### With makefile
```
git clone --recursive https://github.com/timothyschoen/PlugData.git
cd PlugData
take build
cmake -G"Unix Makefiles"
make
sudo make install
```


## Windows
TODO

## Linux
```
git clone --recursive https://github.com/timothyschoen/PlugData.git
cd PlugData
take build
cmake -G"Unix Makefiles"
make
sudo make install
```
