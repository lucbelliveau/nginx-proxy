kubeproxy: kubectl proxy
gen: ${KUBEPREFIX:-"docker"}-gen -watch -${KUBENOTIFY:-notify} "nginx -s reload" /app/nginx-${KUBEPREFIX:-"docker"}.tmpl /etc/nginx/conf.d/default.conf
nginx: nginx
