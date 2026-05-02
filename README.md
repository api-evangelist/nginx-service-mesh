# NGINX Service Mesh (nginx-service-mesh)

NGINX Service Mesh (NSM) is a service mesh from F5 NGINX powered by NGINX Plus, designed to manage container-to-container traffic in Kubernetes environments. It provides mTLS, traffic policies via the Service Mesh Interface (SMI), traffic splitting, rate limiting, observability (Prometheus, Grafana, Jaeger), and integration with the NGINX Plus Ingress Controller. NGINX Service Mesh exposes a control-plane REST API and a `nginx-meshctl` CLI for installation, sidecar injection, certificate management, and policy configuration.

> **Status:** The upstream `nginxinc/nginx-service-mesh` repository is archived. F5 announced End of Sale (EoS) for the NGINX Microservices Bundle as of July 1, 2023. For new ingress and L7 routing workloads, F5 directs users to NGINX Gateway Fabric.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/nginx-service-mesh/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Container Networking
- End of Sale
- F5
- Kubernetes
- mTLS
- NGINX
- Observability
- Service Mesh
- SMI
- Traffic Management

## Timestamps

- **Created:** 2026-04-28
- **Modified:** 2026-04-28

## APIs

### NGINX Service Mesh Control Plane API

The NGINX Service Mesh control plane exposes a REST API used by the `nginx-meshctl` CLI to manage mesh configuration, sidecar injection, certificate authority operations, traffic policies, and resource lookups. The API is internal to the cluster and is not published as a public OpenAPI document; its surface is documented through the API Usage guide and the `nginx-meshctl` reference.

**Human URL:** https://docs.nginx.com/nginx-service-mesh/reference/api-usage/

**Tags:** API, Control Plane, Kubernetes, REST

**Properties:**

- [Documentation](https://docs.nginx.com/nginx-service-mesh/reference/api-usage/)
- [CLI Reference](https://docs.nginx.com/nginx-service-mesh/reference/nginx-meshctl/)
- [GitHub (archived)](https://github.com/nginxinc/nginx-service-mesh)

> Note: No static OpenAPI specification is vendored in this repository because NGINX Service Mesh does not publish a public OpenAPI document for its control plane.

## Common Properties

- [Website](https://docs.nginx.com/nginx-service-mesh/)
- [Documentation](https://docs.nginx.com/nginx-service-mesh/)
- [Getting Started](https://docs.nginx.com/nginx-service-mesh/get-started/)
- [Architecture](https://docs.nginx.com/nginx-service-mesh/about/architecture/)
- [GitHub (archived)](https://github.com/nginxinc/nginx-service-mesh)
- [Successor: NGINX Gateway Fabric](https://docs.nginx.com/nginx-gateway-fabric/)
- [Blog](https://www.f5.com/company/blog/nginx)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
