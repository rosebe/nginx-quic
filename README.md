## nginx-quic
[![build nginx-quic](https://github.com/rosebe/nginx-quic/actions/workflows/build.yml/badge.svg)](https://github.com/rosebe/nginx-quic/actions/workflows/build.yml)
使用GitHub Action编译nginx-quic，基于最新源码（https://hg.nginx.org/nginx-quic)

##### [测试你的浏览器对quic的支持](https://quic.nginx.org/quic.html)
##### [测试服务器对HTTP/3的支持](https://http3check.net)

##### [官方介绍](https://quic.nginx.org/readme.html)


To enable GSO (Generic Segmentation Offloading):

    quic_gso on;

    By default this Linux-specific optimization is disabled.
    Enable if your network interface is configured to support GSO.

##### 注意：--with-http_quic_module       已弃用，请删除该项
