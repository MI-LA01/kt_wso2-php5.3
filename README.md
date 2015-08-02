# kt_wso2-php5.3

## Introduction
KROKNET WSO2 Web Services Framework for PHP 5.3 (WSO2 WSF/PHP), a binding of WSO2 WSF/C into PHP is a PHP extension for providing and consuming Web Services in PHP. WSO2 WSF/PHP supports SOAP 1.1, SOAP 1.2, WSDL 1.1, WSDL 2.0, REST style invocation as well as some of the key WS-* stack specifications such as: SOAP MTOM, WS-Addressing, WS-Security, WS-SecurityPolicy and WS-ReliableMessaging.

## Clone 
```
$ mkdir ~/wso2-wsf-php53 && cd ~/wso2-wsf-php53
$ git clone git@github.com:MI-LA01/kt_wso2-php5.3.git
```

## Libtools
```
$ ./autogen.sh 
```

## Configure
```
$ ./configure CC=gcc-4.4 --enable-tests=no --enable-openssl
```

## Compile / Install
```
$ make
$ make install
```
