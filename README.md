Clone 4.8 branch

````
$ git clone https://git.gitorious.org/qt/qt.git
$ cd qt
$ patch -p0 < qbytearray.patch
$ patch -p0 < qnetworkcookie.patch
$ patch -p0 < qsslsocket_openssl_symbols.patch
$ patch -p0 < qthread_unix.patch
````
