# nginx config
## features
* HTTP/2
* TLS 1.3 (via OpenSSL)
* brotli (via ngx_brotli)

## prepare
* clang-7
* gcc-8
* g++-8
* make

## downloads
### [nginx](https://nginx.org/)
```
wget http://nginx.org/download/nginx-1.15.5.tar.gz
tar xf nginx-1.15.5.tar.gz
``` 
### [OpenSSL](https://www.openssl.org/)
```
wget https://github.com/openssl/openssl/archive/OpenSSL_1_1_1.tar.gz
tar xf OpenSSL_1_1_1.tar.gz
mv openssl-OpenSSL_1_1_1/ openssl/
```
### [PCRE](https://www.pcre.org/)
```
wget https://ftp.pcre.org/pub/pcre/pcre-8.42.tar.gz
tar xf pcre-8.42.tar.gz
```
### [zlib](https://www.zlib.net/)
```
wget https://zlib.net/zlib-1.2.11.tar.gz
tar xf zlib-1.2.11.tar.gz
```
### [ngx_brotli](https://github.com/google/ngx_brotli)
```
git clone https://github.com/eustas/ngx_brotli.git
cd ngx_brotli
git submodule update --init
cd ../
```