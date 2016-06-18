# SpringBoot--ConsulClient
Sample of simple consul client with spring boot.

##Consul discovery client configuration
###Bootstrap.properties
* * *

**spring.application.name=**consul-client-v0
**spring.cloud.consul.host=**${HOSTNAME:localhost}
**spring.cloud.consul.port=**${CONSUL_PORT:8500}
**spring.cloud.consul.discovery.healthCheckInterval=**15s
**spring.cloud.consul.discovery.instanceId=**${spring.application.name}:${spring.application.instanceid:${random.value}}

* * *

