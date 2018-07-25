
ericyu.openresty for Ansible Galaxy
============

## Summary

Role name in Ansible Galaxy: **[ckplus.openresty](https://galaxy.ansible.com/ckplus/ansible_openresty)**
This Ansible role has the following features for [Openresty](https://openresty.org/en/):


### Optional variables: general settings


User-configurable defaults:

```yaml
# user and group
openresty_version: "1.11.2.3"
openresty_install_path: /opt
openresty_install_dir : /opt/openresty
openresty_download_path:     /tmp

sbin_path: /usr/sbin/nginx
conf_path: /etc/nginx/nginx.conf
error_log_path: /var/log/nginx/error.log
http_client_body_temp_path: /var/lib/nginx/body
http_fastcgi_temp_path: /var/lib/nginx/fastcgi
http_log_path: /var/log/nginx/access.log
http_proxy_temp_path: /var/lib/nginx/proxy
http_scgi_temp_path: /var/lib/nginx/scgi
http_uwsgi_temp_path: /var/lib/nginx/uwsgi
lock_path: /var/lock/nginx.lock
pid_path: /var/run/nginx.pid
with_sha1: /usr/include/openssl
with_md5: /usr/include/openssl

nginx_user:               www-data     # uid of worker process
nginx_ulimit:             51200     # worker_rlimit_nofile in nginx.conf
nginx_worker_connections: 1024      # worker_connections in nginx.conf
```