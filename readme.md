https://docs.nginx.com/nginx/admin-guide/load-balancer/tcp-udp-load-balancer/#

https://github.com/kylemcc/kube-nginx-proxy

https://medium.com/@santhoz/nginx-sidecar-reverse-proxy-for-performance-http-to-https-redirection-in-kubernetes-dd9dbe2fd0c7

https://github.com/sclorg/nginx-container/tree/master/examples

https://stackoverflow.com/questions/23399604/rabbitmq-connection-through-nginx

https://serverfault.com/questions/858067/unknown-directive-stream-in-etc-nginx-nginx-conf86

https://www.ruby-forum.com/t/1-9-stream-not-working-directive-is-not-allowed-here/241761/3

http://nginx.org/en/docs/stream/ngx_stream_core_module.html#stream

http://nginx.org/en/docs/stream/ngx_stream_core_module.html#example

https://serverfault.com/questions/858067/unknown-directive-stream-in-etc-nginx-nginx-conf86

https://www.openshift.com/blog/understanding-service-accounts-sccs


oc create serviceaccount useroot

oc adm policy add-scc-to-user anyuid -z useroot --as system:admin

oc create -f deployment.yaml