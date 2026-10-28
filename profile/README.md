<!-- Netcracker / .github / profile/README.md -->

<h1 align="center">Netcracker Open Source</h1>

<p align="center">
  <b>Qubership</b> — cloud-native building blocks for API governance, integration, observability and Kubernetes platforms
</p>

---

## 👋 About

Netcracker engineers build and open-source **Qubership** — a family of production-proven components that power our own cloud platforms: an API registry and developer portal, an integration platform on Apache Camel, the Cloud Core microservice framework and service mesh, a full observability stack, Kubernetes operators for data and messaging services, and the tooling to test, configure and deliver it all.

Every repository is tagged with a domain topic (`qubership-apihub`, `qubership-core`, `qubership-infra`, …), so each card below links to the complete list for its domain.

---

## 🗂 Product Domains

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>🧩 APIHUB</h3>
      <p>API registry and developer portal: one place for OpenAPI, GraphQL and AsyncAPI specs, with versioning, breaking-change detection, linting and MCP access — in one monorepo.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-apihub">qubership-apihub</a> — the platform</li>
        <li>API registry — Go backend</li>
        <li>builder — spec processing &amp; diff pipeline</li>
        <li>web portal, API linter, in-cluster agents</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-apihub">All APIHUB repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>🔗 Cloud Integration Platform</h3>
      <p>Open-source integration and orchestration platform built on Apache Camel: visual flow designer, runtime engines, session tracing and testing — in one monorepo.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-integration-platform">qubership-integration-platform</a> — the platform</li>
        <li>engine &amp; micro-engine — Spring Boot / Quarkus runtimes</li>
        <li>runtime catalog &amp; sessions management</li>
        <li>web UI, VS Code extension, testing service</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-integration">All integration repositories →</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>☁️ Cloud Core &amp; Service Mesh</h3>
      <p>Foundation for microservices on Kubernetes: service mesh control plane and gateways, messaging- and database-as-a-service, Java and Go frameworks.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-core-control-plane">qubership-core-control-plane</a> — service mesh control plane</li>
        <li><a href="https://github.com/Netcracker/qubership-core-ingress-gateway">qubership-core-ingress-gateway</a> — Envoy-based gateway</li>
        <li><a href="https://github.com/Netcracker/qubership-maas">qubership-maas</a> · <a href="https://github.com/Netcracker/qubership-dbaas">qubership-dbaas</a> — messaging &amp; DB as a service</li>
        <li><a href="https://github.com/Netcracker/qubership-core-java-libs">qubership-core-java-libs</a> — Spring &amp; Quarkus libraries</li>
        <li><a href="https://github.com/Netcracker/qubership-core-lib-go">qubership-core-lib-go</a> — Go microservice utilities</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-core">All Cloud Core repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>📈 Observability</h3>
      <p>Monitoring, logging, tracing and profiling for cloud-native platforms — operators, exporters, plugins and OpenTelemetry tooling.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-monitoring-operator">qubership-monitoring-operator</a> — monitoring stack</li>
        <li><a href="https://github.com/Netcracker/qubership-logging-operator">qubership-logging-operator</a> — logging stack</li>
        <li><a href="https://github.com/Netcracker/qubership-jaeger">qubership-jaeger</a> — distributed tracing</li>
        <li><a href="https://github.com/Netcracker/qubership-open-telemetry-collector">qubership-open-telemetry-collector</a> — OTel Collector build</li>
        <li><a href="https://github.com/Netcracker/qubership-profiler-agent">qubership-profiler-agent</a> — Java profiler</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-observability">All observability repositories →</a></p>
    </td>
  </tr>
</table>

<details>
<summary><b>Show 8 more domains</b> — Kubernetes, data services, data processing, delivery, environments, testing, security, AI</summary>
<br>

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>⚓ Kubernetes Platform</h3>
      <p>Cluster lifecycle, disaster recovery and networking for Kubernetes.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/KubeMarine">KubeMarine</a> — cluster deployment &amp; maintenance</li>
        <li><a href="https://github.com/Netcracker/DRNavigator">DRNavigator</a> · <a href="https://github.com/Netcracker/qubership-disaster-recovery-daemon">disaster-recovery-daemon</a> — DR switchover</li>
        <li><a href="https://github.com/Netcracker/qubership-envoy-api-gateway">qubership-envoy-api-gateway</a> — Envoy Gateway chart</li>
        <li><a href="https://github.com/Netcracker/qubership-network-policy-operator">qubership-network-policy-operator</a> — Calico policies</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Ak8sstream">All Kubernetes repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>🗄 Data &amp; Messaging Services</h3>
      <p>Kubernetes operators with backup, monitoring and DBaaS adapters for databases, brokers and storage.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/pgskipper-operator">pgskipper-operator</a> — PostgreSQL (Patroni)</li>
        <li><a href="https://github.com/Netcracker/qubership-kafka">qubership-kafka</a> · <a href="https://github.com/Netcracker/qubership-rabbitmq">qubership-rabbitmq</a> — messaging</li>
        <li><a href="https://github.com/Netcracker/qubership-opensearch">qubership-opensearch</a> · <a href="https://github.com/Netcracker/qubership-cassandra-operator">cassandra-operator</a> · <a href="https://github.com/Netcracker/qubership-mongodb-operator">mongodb-operator</a></li>
        <li><a href="https://github.com/Netcracker/qubership-consul">qubership-consul</a> · <a href="https://github.com/Netcracker/qubership-zookeeper">qubership-zookeeper</a> · <a href="https://github.com/Netcracker/qubership-redis">qubership-redis</a> · <a href="https://github.com/Netcracker/qubership-minio">qubership-minio</a></li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-infra">All infrastructure repositories →</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🌊 Data Processing &amp; Workflows</h3>
      <p>Dataflow, orchestration and analytics engines packaged for Kubernetes.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-nifi">qubership-nifi</a> · <a href="https://github.com/Netcracker/qubership-nifi-registry">nifi-registry</a> — Apache NiFi dataflows</li>
        <li><a href="https://github.com/Netcracker/qubership-airflow">qubership-airflow</a> — workflow orchestration</li>
        <li><a href="https://github.com/Netcracker/qubership-spark-on-k8s">qubership-spark-on-k8s</a> · <a href="https://github.com/Netcracker/qubership-trino">qubership-trino</a> — analytics</li>
        <li><a href="https://github.com/Netcracker/qubership-mistral">qubership-mistral</a> — workflow service</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-nifi">All NiFi repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>🚀 DevOps &amp; Delivery</h3>
      <p>Reusable CI/CD building blocks and pipeline tooling used across the org.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-workflow-hub">qubership-workflow-hub</a> — reusable GitHub Actions</li>
        <li><a href="https://github.com/Netcracker/qubership-pipelines-declarative-executor">qubership-pipelines-declarative-executor</a> — declarative pipelines</li>
        <li><a href="https://github.com/Netcracker/qubership-git-system-follower">qubership-git-system-follower</a> — package manager for Git providers</li>
        <li><a href="https://github.com/Netcracker/qubership-build-info-go">qubership-build-info-go</a> — build-info generator</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-devops">All DevOps repositories →</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🧬 EnvGene</h3>
      <p>Environment generation and configuration management as code.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-envgene">qubership-envgene</a> — environment generator</li>
        <li><a href="https://github.com/Netcracker/qubership-envgene-base-modules">qubership-envgene-base-modules</a> — base modules</li>
        <li><a href="https://github.com/Netcracker/qubership-envgene-template">qubership-envgene-template</a> — starter template</li>
        <li><a href="https://github.com/Netcracker/qubership-cloud-passport-cli">qubership-cloud-passport-cli</a> — cloud passport CLI</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-cm">All EnvGene repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>🧪 Testing Platform</h3>
      <p>Integration testing framework with system stubs, test data management and runners for popular test tools.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-testing-platform-itf-executor">itf-executor</a> · <a href="https://github.com/Netcracker/qubership-testing-platform-itf-stubs">itf-stubs</a> — integrations testing framework</li>
        <li><a href="https://github.com/Netcracker/qubership-testing-platform-tdm">tdm</a> · <a href="https://github.com/Netcracker/qubership-testing-platform-datasets">datasets</a> — test data</li>
        <li><a href="https://github.com/Netcracker/qubership-testing-platform-playwright-runner">playwright</a> · <a href="https://github.com/Netcracker/qubership-testing-platform-bruno-runner">bruno</a> · <a href="https://github.com/Netcracker/qubership-testing-platform-newman-runner">newman</a> runners</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-tp">All testing repositories →</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🔐 Security</h3>
      <p>Authorization, secrets and policy enforcement for Kubernetes workloads.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-authz-agent">qubership-authz-agent</a> — OPA-based authorization proxy</li>
        <li><a href="https://github.com/Netcracker/qubership-openbao">qubership-openbao</a> — secrets management</li>
        <li><a href="https://github.com/Netcracker/qubership-credential-manager">qubership-credential-manager</a> — credentials</li>
        <li><a href="https://github.com/Netcracker/gatekeeper-library">gatekeeper-library</a> — OPA Gatekeeper policies</li>
      </ul>
      <p><a href="https://github.com/orgs/Netcracker/repositories?q=topic%3Aqubership-security">All security repositories →</a></p>
    </td>
    <td valign="top" width="50%">
      <h3>🤖 AI Engineering</h3>
      <p>Tooling for teams working with AI coding agents.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-ai-packages">qubership-ai-packages</a> — skills &amp; instructions for Claude Code, Codex, Cursor, Copilot</li>
        <li><a href="https://github.com/Netcracker/qubership-ai-agent-telemetry">qubership-ai-agent-telemetry</a> — OpenTelemetry for agent runs</li>
        <li><a href="https://github.com/Netcracker/qubership-virtual-secretary">qubership-virtual-secretary</a> — GenAI team assistant</li>
      </ul>
    </td>
  </tr>
</table>

</details>
