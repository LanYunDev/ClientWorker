<p align="center">
<img src="https://unpkg.com/chenyfan-os@0.0.0-r22/ClientWorker.png" alt="ClientWorker" width="20%">
</p>

# ClientWorker

文档地址：[ClientWorker](https://clientworker.js.org)

↑这也是用ClientWorker搭建的！

## 它能干什么


- 绕备，在域名不变动的情况下，其余用户所有请求均可以定向到你的其他服务器或者cdn，而首屏域名无需ICP备案。
- 降本，你可以用廉价的家宽+公网ipv4/ipv6，即使是80/443被封锁，你也可以在不变动端口的情况下将用户流量引向家宽。
- 白嫖，可以用免费的公网穿透服务，接近零成本托管你的服务。
- 加速，将静态资源流量（乃至动态资源）**并发**到全球cdn，实现前端级负载均衡。
- 绕禁，通过在前端修改标头的方式，修复被故意篡改的`MIME`，正常托管网站，绕过各大托管商对于网站部署的限制，可以毫无负担的使用阿里云、腾讯云等对象存储而不用开启网站模式，乃至GithubRaw无限流量（绕过GithubPage 100GB限制）。
- 愈合：通过并发方式，辅助JSDelivr、Unpkg、cdnjs等大陆几乎不可达请求重定向至其他cdn，从而实现无修改、全球加速。
- 不宕机，即使首屏服务器离线或不可达，已访问过的用户依旧可以正常命中备用服务器。
- ...更多玩法等你挖掘

## License

GPL-3.0-or-later