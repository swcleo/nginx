# nginx

開發上常用的 nginx 配置。

## mkcert

mkcert is a simple tool for making locally-trusted development certificates.

生成 nginx 使用的 key、cert

```sh
mkcert -cert-file nginx.crt -key-file nginx.key localhost 127.0.0.1 ::1 www.front.net
```

查看根憑證目錄位置

```sh
mkcert -CAROOT
```
