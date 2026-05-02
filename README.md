# Scalable Services

A curated topic collection covering APIs, patterns, tools, and best practices for designing and operating scalable services. This includes cloud-native microservices, API gateways, load balancers, container orchestration, serverless platforms, service meshes, and the architectural patterns that enable services to scale horizontally and vertically.

**Type:** Topic Collection
**Tags:** API Gateway, Cloud Native, Containers, Distributed Systems, High Availability, Kubernetes, Load Balancing, Microservices, Scalable Architecture, Serverless, Service Mesh

## APIs

### Kubernetes API
Programmatic management of containerized workloads including deployments, services, pods, config maps, and horizontal pod autoscalers. Core to running scalable microservices infrastructure.

- **Documentation:** [https://kubernetes.io/docs/reference/kubernetes-api/](https://kubernetes.io/docs/reference/kubernetes-api/)
- **OpenAPI:** [https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json](https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json)
- **GitHub:** [https://github.com/kubernetes/kubernetes](https://github.com/kubernetes/kubernetes)

### Envoy Admin API
Administration API for inspecting and modifying Envoy runtime configuration, stats, clusters, and listeners. Foundational data plane for service mesh and API gateway deployments.

- **Documentation:** [https://www.envoyproxy.io/docs/envoy/latest/operations/admin](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- **GitHub:** [https://github.com/envoyproxy/envoy](https://github.com/envoyproxy/envoy)

### Istio API
Configuration APIs defining traffic management, security policy, and observability for microservice meshes. Expressed as Kubernetes CRDs (VirtualService, DestinationRule, Gateway, etc.).

- **Documentation:** [https://istio.io/latest/docs/reference/config/](https://istio.io/latest/docs/reference/config/)
- **GitHub:** [https://github.com/istio/istio](https://github.com/istio/istio)

### AWS Lambda API
Amazon Web Services Lambda API for creating, managing, invoking, and monitoring serverless functions. Core to event-driven, auto-scaling architectures.

- **Documentation:** [https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html](https://docs.aws.amazon.com/lambda/latest/api/API_Operations.html)

### Kong Admin API
RESTful Admin API for managing services, routes, plugins, consumers, upstreams, and certificates. Widely deployed open-source API gateway for scalable API management.

- **Documentation:** [https://docs.konghq.com/gateway/latest/admin-api/](https://docs.konghq.com/gateway/latest/admin-api/)
- **GitHub:** [https://github.com/Kong/kong](https://github.com/Kong/kong)

### Prometheus HTTP API
HTTP API for querying metrics, metadata, and alerting rules. Essential for observability and autoscaling decisions in scalable service architectures.

- **Documentation:** [https://prometheus.io/docs/prometheus/latest/querying/api/](https://prometheus.io/docs/prometheus/latest/querying/api/)
- **GitHub:** [https://github.com/prometheus/prometheus](https://github.com/prometheus/prometheus)

### Knative API
Kubernetes-based platform APIs for deploying and scaling event-driven serverless workloads. Includes Knative Serving (scale-to-zero) and Knative Eventing.

- **Documentation:** [https://knative.dev/docs/](https://knative.dev/docs/)
- **GitHub:** [https://github.com/knative/serving](https://github.com/knative/serving)

### gRPC Reflection API
gRPC server reflection for discovery and dynamic invocation. Widely used for high-performance inter-service communication in scalable microservice architectures.

- **Documentation:** [https://grpc.io/docs/](https://grpc.io/docs/)
- **GitHub:** [https://github.com/grpc/grpc](https://github.com/grpc/grpc)

## Artifacts

### JSON Schema
- [Scalable Service Schema](json-schema/scalable-services-service-schema.json) — Schema for a scalable cloud service configuration including scaling policy, load balancing, rate limiting, circuit breaker, and observability.

### JSON Structure
- [Scalable Service Structure](json-structure/scalable-services-service-structure.json) — Structural documentation for scalable service configuration.

### JSON-LD Context
- [Scalable Services Context](json-ld/scalable-services-context.jsonld) — Linked data context mapping scalable services vocabulary to schema.org.

### Vocabulary
- [Scalable Services Vocabulary](vocabulary/scalable-services-vocabulary.yml) — Domain vocabulary covering API Gateway, Auto Scaling, Circuit Breaker, Container, Service Mesh, Serverless, Twelve-Factor App, and Zero Downtime Deployment.

### Examples
- [Kubernetes HPA Example](examples/scalable-services-kubernetes-hpa-example.json) — Kubernetes Horizontal Pod Autoscaler configuration for a scalable microservice.
- [Kong Rate Limiting Plugin](examples/scalable-services-kong-plugin-example.json) — Kong Admin API call to apply a rate limiting plugin protecting a scalable microservice from traffic spikes.

## Common Resources

- [Kubernetes Architecture Concepts](https://kubernetes.io/docs/concepts/architecture/)
- [Microservices Patterns](https://microservices.io/patterns/index.html)
- [CNCF Landscape Projects](https://www.cncf.io/projects/)
- [What is a Service Mesh?](https://istio.io/latest/about/service-mesh/)
- [Envoy Service Mesh Guide](https://www.envoyproxy.io/learn/service-mesh)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
