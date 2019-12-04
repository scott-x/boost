# boost

[boost](https://www.boost.org/), a c++ Lib common, which was used in many places.

### install on Mac

```shell
cd /usr/local/include
wget --no-check-certifacate https://dl.bintray.com/boostorg/release/1.71.0/source/boost_1_71_0.tar.gz
tar -zxvf boost_1_71_0.tar.gz
sudo ln -sv boost_1_71_0/boost boost
rm -rf boost_1_71_0.tar.gz
echo "install success!"
```

### uninstall

```shell
#unlink path
unlink /usr/local/include/boost
```