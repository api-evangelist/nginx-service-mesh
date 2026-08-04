# NGINX Service Mesh (nginx-service-mesh)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
