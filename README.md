# Scalable Services (scalable-services)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that enable services to scale horizontally and vertically. Relevant to platform engineers, cloud architects, and backend developers building high-traffic, distributed systems.

## Scope

- **Type:** Index

## Tags

- API Gateway
- Cloud Native
- Containers
- Distributed Systems
- High Availability
- Kubernetes
- Load Balancing
- Microservices
- Scalable Architecture
- Serverless
- Service Mesh

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-05-02

## APIs

### Kubernetes API

The Kubernetes API enables programmatic management of containerized workloads, including deployments, services, pods, config maps, and horizontal pod autoscalers. Core to running scalable microservices infrastructure.

- **Human URL:** [https://kubernetes.io/docs/reference/kubernetes-api/](https://kubernetes.io/docs/reference/kubernetes-api/)

#### Tags

- Containers
- Kubernetes
- Orchestration
- Scalable Architecture

#### Properties

- [Documentation](https://kubernetes.io/docs/reference/kubernetes-api/)
- [OpenAPI](https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://kubernetes.io/docs/home/)
- [Git Hub](https://github.com/kubernetes/kubernetes)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy Admin API

Envoy Proxy's administration API for inspecting and modifying Envoy runtime configuration, stats, clusters, and listeners. Envoy is the foundational data plane for many service mesh and API gateway deployments.

- **Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/operations/admin](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)

#### Tags

- API Gateway
- Load Balancing
- Proxy
- Service Mesh

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- [Git Hub](https://github.com/envoyproxy/envoy)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Istio API

Istio's configuration APIs define traffic management, security policy, and observability for microservice meshes. Expressed as Kubernetes CRDs (VirtualService, DestinationRule, Gateway, etc.).

- **Human URL:** [https://istio.io/latest/docs/reference/config/](https://istio.io/latest/docs/reference/config/)

#### Tags

- Kubernetes
- Microservices
- Observability
- Security
- Service Mesh

#### Properties

- [Documentation](https://istio.io/latest/docs/reference/config/)
- [Git Hub](https://github.com/istio/istio)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS Lambda API

Amazon Web Services Lambda API for creating, managing, invoking, and monitoring serverless functions. Core to event-driven, auto-scaling architectures.

- **Human URL:** [https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html](https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html)

#### Tags

- AWS
- Cloud Native
- Event Driven
- Scalable Architecture
- Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong Admin API

Kong Gateway's RESTful Admin API for managing services, routes, plugins, consumers, upstreams, and certificates. Kong is a widely deployed open-source API gateway for scalable API management.

- **Human URL:** [https://docs.konghq.com/gateway/latest/admin-api/](https://docs.konghq.com/gateway/latest/admin-api/)

#### Tags

- API Gateway
- Load Balancing
- Microservices
- Plugins

#### Properties

- [Documentation](https://docs.konghq.com/gateway/latest/admin-api/)
- [Git Hub](https://github.com/Kong/kong)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prometheus HTTP API

Prometheus exposes an HTTP API for querying metrics, metadata, and alerting rules. Essential for observability and autoscaling decisions in scalable service architectures.

- **Human URL:** [https://prometheus.io/docs/prometheus/latest/querying/api/](https://prometheus.io/docs/prometheus/latest/querying/api/)

#### Tags

- Alerts
- Metrics
- Monitoring
- Observability

#### Properties

- [Documentation](https://prometheus.io/docs/prometheus/latest/querying/api/)
- [Git Hub](https://github.com/prometheus/prometheus)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Knative API

Knative provides Kubernetes-based platform APIs for deploying and scaling event-driven serverless workloads. Includes Knative Serving (scale-to-zero) and Knative Eventing (event sourcing and routing).

- **Human URL:** [https://knative.dev/docs/](https://knative.dev/docs/)

#### Tags

- Cloud Native
- Event Driven
- Kubernetes
- Scalable Architecture
- Serverless

#### Properties

- [Documentation](https://knative.dev/docs/)
- [Git Hub](https://github.com/knative/serving)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### gRPC Reflection API

gRPC server reflection provides information about publicly-accessible gRPC services on a server, enabling discovery and dynamic invocation. gRPC is widely used for high-performance inter-service communication in scalable microservice architectures.

- **Human URL:** [https://grpc.io/docs/](https://grpc.io/docs/)

#### Tags

- High Performance
- Microservices
- Protocol Buffers
- RPC

#### Properties

- [Documentation](https://grpc.io/docs/)
- [Git Hub](https://github.com/grpc/grpc)
- [Postman Collection](collections/scalable-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://kubernetes.io/docs/concepts/architecture/)
- [Guide](https://microservices.io/patterns/index.html)
- [Guide](https://www.cncf.io/projects/)
- [Guide](https://istio.io/latest/about/service-mesh/)
- [Guide](https://www.envoyproxy.io/learn/service-mesh)
- [JSON Schema](https://github.com/api-evangelist/scalable-services/blob/main/json-schema/scalable-services-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://github.com/api-evangelist/scalable-services/blob/main/json-structure/scalable-services-service-structure.json)
- [J S O N L D Context](https://github.com/api-evangelist/scalable-services/blob/main/json-ld/scalable-services-context.jsonld)
- [Vocabulary](https://github.com/api-evangelist/scalable-services/blob/main/vocabulary/scalable-services-vocabulary.yml)
- [Examples](https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kubernetes-hpa-example.json)
- [Examples](https://github.com/api-evangelist/scalable-services/blob/main/examples/scalable-services-kong-plugin-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
