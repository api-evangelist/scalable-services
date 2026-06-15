# Scalable Services (scalable-services)

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
