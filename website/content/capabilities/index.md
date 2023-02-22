---
title: Capabilities of Platforms
description: A more in-depth look into the functions of Platforms and how they provide value
weight: 5
---

<!-- ## <i class="fas fa-users"></i> People  -->
As described earlier, a platform for cloud-native computing offers and composes
capabilities and services from many supporting providers. These providers may be
other teams within the same enterprise or third parties like "cloud" service
providers. Platforms enable use of the capabilities and services from these
providers by wrapping them with consistent web portals, documentation, code
templates, and programmable APIs and tools. 

In a nutshell, platforms bridge from underlying capability _providers_ to
platform users like application developers; and in the process implement and
enforce desired practices for security, performance, cost governance and
consistent experience. The following graphic illustrates the relationships
between product, platform, and capability providers.

<img src="/images/platform_components.png" width=600px />

We've described the attributes and values of platforms and platform teams. Now
let's describe the kinds of capabilities typically required in cloud-native
computing platforms. Our goal is to guide platform engineers in ensuring their
platform is complete.

1. **Web portal** for provisioning and observing capabilities
1. **APIs** (and CLIs) for automatically provisioning capabilities
1. **"Golden path" templates and docs** enabling optimal use of capabilities
1. **Automation for building and testing** services and products
1. **Automation for delivering and verifying** services and products
1. **Development environments**: hosted IDEs, remote connection tools
1. Instrumentation and dashboards to enable **observability** of services and
   products, including function, performance and cost
1. **Infrastructure** services: compute runtimes, programmable networks, block
   and volume storage
1. **Data** services: databases, caches, object stores
1. **Messaging** and event services: brokers, queues, event fabrics
1. **Identity and secret** management services: service and user identity and
   authorization, certificate and key issuance, static secret storage
1. **Security** services: static analysis of code and artifacts, runtime analysis,
   policy enforcement
1. **Artifact storage**: container image and language-specific package management,
   custom binaries and libraries, source code

<table>
  <thead>
    <tr><td>Capability</td><td>Description</td><td>Example CNCF/CDF Projects</td></tr>
  </thead>
  <tr>
    <td>Web portals for provisioning and observing capabilities</td>
    <td>Publish documentation, service catalogs, and project templates. Publish telemetry about systems and capabilities.</td>
    <td>Backstage</td>
  </tr>
  <tr>
    <td>APIs for automatically provisioning capabilities</td>
    <td>Structured formats for automatically creating, updating, deleting and observing capabilities.</td>
    <td>Kubernetes, Crossplane, Operator Framework, Helm</td>
  </tr>
  <tr>
    <td>Golden path templates and docs</td>
    <td>Templated compositions of well-integrated code and capabilities for rapid project development.</td>
    <td>ArtifactHub</td>
  </tr>
  <tr>
    <td>Automation for building and testing products</td>
    <td>Automate build and test of digital products and services.</td>
    <td>Tekton, Jenkins, Buildpacks, ko, Carvel</td>
  </tr>
  <tr>
    <td>Automation for delivering and verifying services</td>
    <td>Automate and observe delivery of services.</td>
    <td>Argo, Flux, Keptn, Flagger, OpenFeature</td>
  </tr>
  <tr>
    <td>Development environments</td>
    <td>Enable research and development of applications and systems.</td>
    <td>Devfile, Nocalhost, Telepresence, DevSpace</td>
  </tr>
  <tr>
    <td>Application observability</td>
    <td>Instrument applications, gather and analyze telemetry and publish info to stakeholders.</td>
    <td>OpenTelemetry, Jaeger, Prometheus, Thanos, Fluentd, Grafana, OpenCost</td>
  </tr>
  <tr>
    <td>Infrastructure services</td>
    <td>Run application code, connect application components and persist data for applications</td>
    <td>Kubernetes, Kubevirt, Knative, WasmEdge<br />CNI, Istio, Cilium, Envoy, Linkerd, CoreDNS<br />Rook, Longhorn, Etcd</td>
  </tr>
  <tr>
    <td>Data services</td>
    <td>Persist structured data for applications</td>
    <td>TiKV, Vitess, SchemaHero</td>
  </tr>
  <tr>
    <td>Messaging and event services</td>
    <td>Enable applications to communicate with each other asynchronously</td>
    <td>Strimzi, NATS, gRPC, Knative, Dapr</td>
  </tr>
  <tr>
    <td>Identity and secret services</td>
    <td>Ensure workloads have locators and secrets to use resources and capabilities. Enable services to identify themselves to other services</td>
    <td>Dex, External Secrets, SPIFFE/SPIRE, Teller, cert-manager</td>
  </tr>
  <tr>
    <td>Security services</td>
    <td>Observe runtime behavior and report/remediate anomalies. Verify builds and artifacts don't contain vulnerabilities. Constrain activities on the platform per enterprise requirements; notify and/or remediate aberrations</td>
    <td>Falco, In-toto, KubeArmor, OPA, Kyverno, Cloud Custodian</td>
  </tr>
  <tr>
    <td>Artifact storage </td>
    <td>Store, publish and secure built artifacts for use in production. Cache and analyze third-party artifacts. Store source code.</td>
    <td>ArtifactHub, Harbor, Distribution, Porter</td>
  </tr>
</table>