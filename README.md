# nginx config
## features
* HTTP/2
* TLS 1.3 (via OpenSSL)
* brotli (via ngx_brotli)

## prepare
* clang-10
* gcc-8
* g++-8
* make

## downloads
### [nginx](https://nginx.org/)
```
wget https://nginx.org/download/nginx-1.19.0.tar.gz
tar xf nginx-1.19.0.tar.gz
``` 
### [OpenSSL](https://www.openssl.org/)
```
wget https://www.openssl.org/source/openssl-3.0.0-alpha4.tar.gz
tar xf openssl-3.0.0-alpha4.tar.gz
mv openssl-3.0.0-alpha4/ openssl/
```
### [PCRE](https://www.pcre.org/)
```
wget https://ftp.pcre.org/pub/pcre/pcre-8.44.tar.gz
tar xf pcre-8.44.tar.gz
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
