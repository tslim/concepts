# Envoy Proxy

Originally built at Lyft, [Envoy](https://www.envoyproxy.io/) is a high performance C++ [[distributed]] proxy designed for single services and applications, as well as a communication bus and “universal data plane” designed for large microservice [[service-mesh]] architectures.

Built on the learnings of solutions such as NGINX, HAProxy, hardware load balancers, and cloud [[load-balancer]], Envoy runs alongside every application ([[sidecar-service]]) and abstracts the network by providing common features in a platform-agnostic manner. When all service traffic in an infrastructure flows via an Envoy mesh, it becomes easy to visualize problem areas via consistent observability, tune overall performance, and add substrate features in a single place.

[//begin]: # "Autogenerated link references for markdown compatibility"
[distributed]: distributed "Distributed Systems"
[service-mesh]: service-mesh "Service Mesh"
[load-balancer]: load-balancer "Load Balancer"
[sidecar-service]: sidecar-service "Sidecar Service"
[//end]: # "Autogenerated link references"
