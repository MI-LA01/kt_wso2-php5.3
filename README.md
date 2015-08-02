# kt_wso2-php5.3

## Clone 
```
$ mkdir ~/wso2-wsf-php53 && cd ~/wso2-wsf-php53
$ git clone git@github.com:MI-LA01/kt_wso2-php5.3.git
```

## Libtools
```
$ autoreconf -fsi
```

## Configure
```
$ ./configure --enable-libxml2=yes  CC=gcc-4.4 --enable-tests=no --enable-guththila=no --enable-openssl
```

## Compile / Install

```
$ make
$ make install
```
