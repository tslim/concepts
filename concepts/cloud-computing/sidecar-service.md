# Sidecar Service

Sidecars are supporting processes or services that are deployed with the primary application. On a motorcycle, the sidecar is attached to one motorcycle, and each motorcycle can have its own sidecar. In the same way, a sidecar service shares the fate of its parent application.

In [[kubernetes]], a sidecar is just a [[container]] that runs on the same Pod as the application container, because it shares the same volume and network as the main container, it can “help” or enhance how the application operates. Common examples of sidecar containers are log shippers, log watchers, monitoring agents, [[envoy-proxy]] among others.

[//begin]: # "Autogenerated link references for markdown compatibility"
[kubernetes]: kubernetes "Kubernetes (k8s)"
[container]: container "Container"
[envoy-proxy]: envoy-proxy "Envoy Proxy"
[//end]: # "Autogenerated link references"
