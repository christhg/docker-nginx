# docker-nginx
## 單機模式
1. nginx/nginx.conf文件,映射預設配置/etc/nginx/nginx.conf文件
2. nginx/conf.d目錄,映射/etc/nginx/conf.d目錄
3. log目錄,映射預設/var/log/nginx目錄
4. www目錄,映射/usr/share/nginx/html站台目錄

## nginx配置文件
+ nginx/nginx.conf配置全局
+ nginx/conf.d/default.conf 配置80端口...預設index.html
+ nginx/conf.d/proxy_ha.conf 配置代理
+ nginx/conf.d/proxy_oa.conf 配置代理

## Docker-compose
docker-compose.yml

## vi /etc/hosts
ip yourdomain.name
