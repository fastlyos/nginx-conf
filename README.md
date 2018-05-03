# nginx config
## features
* HTTP/2
* TLS 1.3 (via OpenSSL)
* brotli (via ngx_brotli)

## prepare
Install `gcc` and `git`:
```
apt install git build-essential gcc g++ make
```
## downloads
### [nginx](https://nginx.org/)
```
wget https://nginx.org/download/nginx-1.13.12.tar.gz
tar -xf nginx-1.13.12.tar.gz
``` 
### [OpenSSL](https://www.openssl.org/)
```
git clone --single-branch https://github.com/openssl/openssl.git
```
### [PCRE](https://www.pcre.org/)
```
wget https://ftp.pcre.org/pub/pcre/pcre-8.42.tar.gz
tar -xf pcre-8.42.tar.gz
```
### [zlib](https://www.zlib.net/)
```
wget https://zlib.net/zlib-1.2.11.tar.gz
tar -xf zlib-1.2.11.tar.gz
```
### [ngx_brotli](https://github.com/google/ngx_brotli)
```
git clone https://github.com/google/ngx_brotli.git
cd ngx_brotli
git submodule update --init
cd ../
```