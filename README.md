## nginx-quic
[![build nginx_quic_Compiler-GCC](https://github.com/rosebe/nginx-quic/actions/workflows/build-patch-zlib_ng-http_geoip2_module_Compiler-GCC_test-2.yml/badge.svg)](https://github.com/rosebe/nginx-quic/actions/workflows/build-patch-zlib_ng-http_geoip2_module_Compiler-GCC_test-2.yml)
[![build nginx_quic_musl-gcc](https://github.com/rosebe/nginx-quic/actions/workflows/build-patch-zlib_ng-http_geoip2_module_musl-gcc-test-2.yml/badge.svg)](https://github.com/rosebe/nginx-quic/actions/workflows/build-patch-zlib_ng-http_geoip2_module_musl-gcc-test-2.yml)

使用GitHub Action编译nginx-quic，基于最新源码 :<br>
(https://github.com/nginx)<br>
(https://hg.nginx.org/nginx-quic) <br>

#### [测试你的浏览器对quic的支持](https://quic.nginx.org/quic.html)
#### [测试服务器对HTTP/3的支持](https://http3check.net)

#### [官方介绍](https://quic.nginx.org/readme.html)


To enable GSO (Generic Segmentation Offloading):<br>
    quic_gso on;<br>
    By default this Linux-specific optimization is disabled.<br>
    Enable if your network interface is configured to support GSO.<br>

##### 注意：--with-http_quic_module ; --with-stream_quic_module 已弃用，请删除该项
