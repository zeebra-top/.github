<!-- ===================================================== -->
<!-- Netcracker / .github/profile/README.md                -->
<!-- ===================================================== -->

<h1 align="center">Netcracker Open Source</h1>
<p align="center">
  Enterprise-grade cloud platforms, integration tooling, observability stack, API governance and platform engineering.
</p>

<p align="center">
  <a href="#-product-domains">Product Domains</a> •
  <a href="#-quick-navigation">Quick Navigation</a> •
  <a href="#-engineering-catalog">Engineering Catalog</a> •
  <a href="#-how-this-org-is-organized">How This Org Is Organized</a>
</p>

---

## 👋 About

Netcracker engineers publish open-source projects spanning:
- API management and developer portal tooling
- integration and runtime orchestration
- observability and telemetry
- cloud core / service mesh / shared platform services
- infrastructure components for Kubernetes platforms
- configuration and environment generation

This profile is organized around **business / platform domains inferred from repository topics**.

---

## 🗂 Product Domains

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>🧩 API Management &amp; Developer Portal</h3>
      <p><b>Primary topics:</b> <code>qubership-apihub</code>, <code>apihub</code>, <code>frontend</code></p>
      <p>Catalog, browse, compare, lint and render API specifications across formats.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-apihub">qubership-apihub</a> — solution hub and docs</li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-backend">qubership-apihub-backend</a> — registry / backend API</li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-ui">qubership-apihub-ui</a> — web portal</li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-apispec-view">qubership-apihub-apispec-view</a> — spec rendering component</li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-api-processor">qubership-apihub-api-processor</a> — spec processing pipeline</li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-api-diff">qubership-apihub-api-diff</a> — API diff utilities</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>🔗 Integration Platform</h3>
      <p><b>Primary topics:</b> <code>qip</code>, <code>qubership-integration</code></p>
      <p>Flow orchestration, runtime engine, sessions and supporting components for integration workloads.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-integration-platform">qubership-integration-platform</a> — platform umbrella repo</li>
        <li><a href="https://github.com/Netcracker/qubership-integration-engine">qubership-integration-engine</a> — engine runtime</li>
        <li><a href="https://github.com/Netcracker/qubership-integration-runtime-catalog">qubership-integration-runtime-catalog</a> — runtime catalog</li>
        <li><a href="https://github.com/Netcracker/qubership-integration-sessions-management">qubership-integration-sessions-management</a> — session search &amp; analytics</li>
        <li><a href="https://github.com/Netcracker/qubership-integration-checkstyle">qubership-integration-checkstyle</a> — shared integration engineering rules</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>📈 Observability</h3>
      <p><b>Primary topics:</b> <code>qubership-observability</code>, <code>observability</code>, <code>monitoring</code>, <code>logging</code>, <code>profiler</code></p>
      <p>Monitoring, logging, tracing and profiling components for cloud-native platforms.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-monitoring-operator">qubership-monitoring-operator</a> — monitoring stack operator</li>
        <li><a href="https://github.com/Netcracker/qubership-logging-operator">qubership-logging-operator</a> — logging operator</li>
        <li><a href="https://github.com/Netcracker/qubership-profiler-agent">qubership-profiler-agent</a> — profiling agent</li>
        <li><a href="https://github.com/Netcracker/qubership-profiler-backend">qubership-profiler-backend</a> — profiler backend / archival note</li>
        <li><a href="https://github.com/Netcracker/qubership-log-generator">qubership-log-generator</a> — synthetic logging tool</li>
        <li><a href="https://github.com/Netcracker/qubership-external-logging-installer">qubership-external-logging-installer</a> — Graylog installer roles</li>
        <li><a href="https://github.com/Netcracker/qubership-jaeger">qubership-jaeger</a> — Jaeger deployment charts</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>🏗 Core Platform &amp; Service Mesh</h3>
      <p><b>Primary topics:</b> <code>qubership-core</code>, <code>core</code>, <code>service-mesh</code>, <code>cloud-core</code>, <code>maas</code>, <code>lib</code></p>
      <p>Shared platform building blocks, service mesh control plane and foundational libraries.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-core-infra">qubership-core-infra</a> — common cloud-core resources</li>
        <li><a href="https://github.com/Netcracker/qubership-core-control-plane">qubership-core-control-plane</a> — service mesh control plane</li>
        <li><a href="https://github.com/Netcracker/qubership-core-site-management">qubership-core-site-management</a> — site management APIs</li>
        <li><a href="https://github.com/Netcracker/qubership-core-bootstrap">qubership-core-bootstrap</a> — bootstrap / templates</li>
        <li><a href="https://github.com/Netcracker/qubership-core-microservice-framework">qubership-core-microservice-framework</a> — framework base</li>
        <li><a href="https://github.com/Netcracker/qubership-core-process-orchestrator">qubership-core-process-orchestrator</a> — process orchestration</li>
        <li><a href="https://github.com/Netcracker/qubership-core-maas-agent">qubership-core-maas-agent</a> — MaaS proxy / agent</li>
        <li><a href="https://github.com/Netcracker/qubership-maas-declarative-client-spring">qubership-maas-declarative-client-spring</a> — Spring client</li>
        <li><a href="https://github.com/Netcracker/qubership-core-lib-go-maas-core">qubership-core-lib-go-maas-core</a> — Go MaaS client core</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🛠 Infrastructure Data &amp; Runtime Services</h3>
      <p><b>Primary topics:</b> <code>qubership-infra</code>, <code>saqs</code>, plus product-specific tags like <code>kafka</code>, <code>consul</code>, <code>opensearch</code>, <code>zookeeper</code></p>
      <p>Operational data services and infrastructure components used inside cloud environments.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-kafka">qubership-kafka</a> — Kafka service stack</li>
        <li><a href="https://github.com/Netcracker/qubership-consul">qubership-consul</a> — Consul-based service mesh / discovery component</li>
        <li><a href="https://github.com/Netcracker/qubership-opensearch">qubership-opensearch</a> — OpenSearch platform deployment</li>
        <li><a href="https://github.com/Netcracker/qubership-zookeeper">qubership-zookeeper</a> — ZooKeeper service stack</li>
        <li><a href="https://github.com/Netcracker/qubership-airflow">qubership-airflow</a> — Airflow packaging / operations</li>
        <li><a href="https://github.com/Netcracker/qubership-credential-manager">qubership-credential-manager</a> — infra credential component</li>
        <li><a href="https://github.com/Netcracker/qubership-dbaas-adapter-core">qubership-dbaas-adapter-core</a> — DBaaS adapter base library</li>
        <li><a href="https://github.com/Netcracker/qubership-docker-integration-tests">qubership-docker-integration-tests</a> — infra-focused integration tests</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>🧬 Configuration Management &amp; Environment Generation</h3>
      <p><b>Primary topics:</b> <code>qubership-cm</code></p>
      <p>Environment generation and config-oriented tooling.</p>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-envgene">qubership-envgene</a> — environment generation tool</li>
        <li><a href="https://github.com/Netcracker/qubership-envgene-base-modules">qubership-envgene-base-modules</a> — base modules</li>
      </ul>
      <p><i>Small but clearly separated domain by topic convention.</i></p>
    </td>
  </tr>
</table>

---

## ⚡ Quick Navigation

<table>
  <tr>
    <td valign="top" width="33%">
      <b>For API teams</b>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-apihub">APIHUB</a></li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-backend">Registry backend</a></li>
        <li><a href="https://github.com/Netcracker/qubership-apihub-ui">Developer portal UI</a></li>
      </ul>
    </td>
    <td valign="top" width="33%">
      <b>For integration teams</b>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-integration-platform">Integration platform</a></li>
        <li><a href="https://github.com/Netcracker/qubership-integration-engine">Integration engine</a></li>
        <li><a href="https://github.com/Netcracker/qubership-integration-sessions-management">Sessions management</a></li>
      </ul>
    </td>
    <td valign="top" width="33%">
      <b>For platform teams</b>
      <ul>
        <li><a href="https://github.com/Netcracker/qubership-core-control-plane">Service mesh control plane</a></li>
        <li><a href="https://github.com/Netcracker/qubership-monitoring-operator">Monitoring operator</a></li>
        <li><a href="https://github.com/Netcracker/qubership-kafka">Kafka</a></li>
      </ul>
    </td>
  </tr>
</table>

---

## 📚 Engineering Catalog

### Domain → topic mapping

| Domain | Topics that appear to define it |
|---|---|
| API Management & Developer Portal | `qubership-apihub`, `apihub`, `frontend` |
| Integration Platform | `qip`, `qubership-integration` |
| Observability | `qubership-observability`, `observability`, `monitoring`, `logging`, `profiler` |
| Core Platform & Service Mesh | `qubership-core`, `core`, `service-mesh`, `cloud-core`, `maas`, `lib` |
| Infrastructure Data & Runtime Services | `qubership-infra`, `saqs`, `kafka`, `consul`, `opensearch`, `zookeeper` |
| Configuration Management | `qubership-cm` |

### Suggested pinned repositories

If you want the GitHub org homepage to feel like a product portal, pin a balanced set of repos such as:

1. `qubership-apihub`
2. `qubership-integration-platform`
3. `qubership-monitoring-operator`
4. `qubership-core-control-plane`
5. `qubership-kafka`
6. `KubeMarine`

This gives visitors an immediate cross-section of product, platform and infrastructure capabilities.

---

## 🧭 How this org is organized

The repository naming and visible topics suggest a portfolio organized around a few large Qubership domains:

- **APIHUB** for API governance and portal experiences
- **QIP** for integration and runtime flows
- **Observability** for monitoring, logging, profiling and tracing
- **Core / Cloud Core** for platform foundations and service mesh
- **Infra** for operational dependencies and runtime services
- **CM** for environment/config generation

For best results, keep topics consistent and use them as a stable taxonomy:

- domain topic — e.g. `qubership-apihub`
- subdomain topic — e.g. `monitoring`, `logging`, `profiler`
- technical layer — e.g. `frontend`, `lib`, `operator`
- runtime product tag — e.g. `kafka`, `opensearch`, `consul`

---

## 🔎 Browse by topic

GitHub search shortcuts:

- [`org:Netcracker topic:qubership-apihub`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-apihub&type=repositories)
- [`org:Netcracker topic:qubership-integration`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-integration&type=repositories)
- [`org:Netcracker topic:qubership-observability`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-observability&type=repositories)
- [`org:Netcracker topic:qubership-core`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-core&type=repositories)
- [`org:Netcracker topic:qubership-infra`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-infra&type=repositories)
- [`org:Netcracker topic:qubership-cm`](https://github.com/search?q=org%3ANetcracker+topic%3Aqubership-cm&type=repositories)

---

## 🤝 Contribution

Please check repository-level contributing guides, code of conduct and security policy in the target project before submitting changes.

---

<p align="center">
  Built as a discoverable catalog for the Netcracker open-source ecosystem.
</p>
