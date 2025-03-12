please install jsoncpp

```bash
git clone --depth=1 https://github.com/open-source-parsers/jsoncpp.git
cd jsoncpp
mkdir build
cd build
cmake .. -DBUILD_SHARED_LIBS=ON
make
make install
```
