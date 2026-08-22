# Awesome-API-Security

Top API Security Platforms Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on API Discovery, API Posture Management, API Threat Detection, Runtime Protection & API Security Testing
Last updated: August 2026

This repository tracks notable SaaS platforms and open-source projects for API Security. These tools discover and inventory APIs, identify shadow and zombie APIs, detect vulnerabilities and misconfigurations, protect APIs at runtime, enforce authentication and authorization policies, validate API specifications, and automate API security testing.

Examples include Salt Security, Noname Security, 42Crunch, Traceable AI, Cequence Security, Akamai API Security, Imperva API Security, Ping Identity API Intelligence, Cloudflare API Shield, and Wallarm (the category leaders).

Open-source emphasis: This section is heavily expanded with major active projects covering API gateways, API discovery, API observability, OpenAPI governance, API fuzzing, DAST, WAFs, policy enforcement, and vulnerable API training environments — ideal for security teams and developers building transparent, self-hosted API security stacks.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Additional Strong Open-Source Options

Building a Custom Open-Source API Security Stack

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Salt Security

API security platform focused on API discovery, API posture management, behavioral analysis, vulnerability identification, and runtime threat protection.

Noname Security

API security platform providing API discovery, inventory, posture management, risk analysis, runtime protection, and API governance.

42Crunch

API security platform centered around OpenAPI security auditing, API testing, API governance, conformance validation, and runtime protection.

Traceable AI

API security platform providing API discovery, runtime intelligence, behavioral analytics, vulnerability detection, and attack protection.

Cequence Security

Unified API and application protection platform covering API discovery, API security posture, bot management, threat detection, and runtime protection.

Akamai API Security

API security capabilities integrated with Akamai's edge and application security platform for API discovery, risk analysis, and threat protection.

Imperva API Security

API security platform offering API discovery, endpoint risk assessment, sensitive-data identification, behavioral monitoring, and runtime protection.

Ping Identity API Intelligence

API intelligence and security capabilities within the Ping Identity ecosystem, supporting API visibility, access management, authentication, and security analytics.

Cloudflare API Shield

API security capabilities including API discovery, schema validation, mTLS, authentication, and edge-based API protection.

Wallarm

API and application security platform focused on API discovery, vulnerability detection, API threat prevention, and runtime attack detection.

Additional Notable SaaS / Hosted Options

Akamai App & API Protector

WAAP platform combining WAF, bot management, DDoS protection, and API security capabilities.

Fastly Next-Gen WAF

Edge-based application and API protection platform with WAF, bot mitigation, and security observability.

F5 Distributed Cloud API Security

API discovery, risk assessment, posture management, and runtime API protection integrated into F5's distributed cloud security platform.

AWS WAF

Managed AWS web application firewall that can be deployed to protect APIs and applications against common web exploits and malicious traffic.

Microsoft Defender for APIs

Cloud security capabilities for discovering, assessing, and monitoring API security risks within Microsoft Defender for Cloud.

Google Cloud Armor

Managed edge security service providing WAF and DDoS protection that can be deployed in front of API workloads.

Astrix Security

SaaS security platform focused on non-human identities, machine-to-machine connections, and API/service-account risks.

Apono

Identity and access platform supporting just-in-time access and authorization controls across infrastructure, applications, and APIs.

Open-Source GitHub Projects
API Security Platforms & Discovery

Akto

Open-source API security platform providing API discovery, security testing, vulnerability detection, and API security workflows.

APIClarity

Open-source API observability and security platform designed to discover APIs from traffic, analyze API behavior, and identify security risks.

OWASP API Security Project

OWASP project dedicated to API security guidance, best practices, testing methodologies, and the OWASP API Security Top 10.

OWASP crAPI

Vulnerable-by-design API application specifically created for learning, practicing, and demonstrating API security vulnerabilities.

OWASP Juice Shop

Intentionally vulnerable application containing numerous web and API security vulnerabilities for security training and testing.

API Gateways & Runtime Protection

Apache APISIX

Open-source cloud-native API gateway supporting authentication, authorization, rate limiting, traffic management, TLS, and security plugins.

Kong Gateway

Open-source API gateway with authentication, authorization, rate limiting, traffic policies, plugins, and service-to-service security controls.

Tyk

Open-source API gateway and management platform supporting authentication, authorization, rate limiting, analytics, and API policies.

Gravitee API Management

Open-source API management ecosystem with API gateway, policy enforcement, access management, and lifecycle management.

KrakenD Community Edition

Open-source stateless API gateway and aggregation layer with authentication, rate limiting, request manipulation, and traffic controls.

Envoy Proxy

High-performance open-source proxy providing TLS, authorization, rate limiting, traffic management, and observability building blocks for API security.

Traefik

Open-source cloud-native reverse proxy and ingress controller with TLS, authentication middleware, rate limiting, and routing controls.

Caddy

Open-source web server and reverse proxy with automatic HTTPS and extensible middleware useful for securing API ingress.

API Security Testing & Fuzzing

OWASP ZAP

Open-source web application security scanner with API/OpenAPI support, passive scanning, active scanning, automation, and scripting.

Schemathesis

Open-source API testing framework that generates property-based tests from OpenAPI and GraphQL schemas to discover edge cases and security issues.

RESTler

Microsoft's open-source REST API fuzzing engine capable of generating stateful API tests and finding bugs and security vulnerabilities.

EvoMaster

Open-source automated API test-generation tool using search-based techniques for REST and GraphQL services.

Wfuzz

Open-source web application fuzzing framework useful for testing API parameters, endpoints, authentication mechanisms, and request handling.

ffuf

Fast open-source web fuzzer useful for discovering hidden API endpoints, parameters, files, and virtual hosts.

Nuclei

Open-source vulnerability scanner using customizable templates for automated detection of API, web, and infrastructure vulnerabilities.

HTTPX

Open-source HTTP probing and service-discovery toolkit useful for identifying live API endpoints and enriching attack-surface inventories.

Katana

Open-source crawler designed for discovering web and API endpoints across modern applications.

Kiterunner

Open-source API content-discovery tool designed to identify hidden API routes and endpoints using API-aware request techniques.

Arjun

Open-source HTTP parameter discovery tool useful for identifying undocumented API parameters.

Param Miner

Open-source Burp Suite extension for discovering hidden parameters and headers that may expose undocumented API functionality.

OpenAPI & API Contract Security

Spectral

Open-source JSON/YAML linting engine widely used for OpenAPI quality, security, governance, and API-style enforcement.

Optic

Open-source API contract and change-detection tooling that compares API behavior with OpenAPI specifications.

OpenAPI Generator

Open-source toolkit for generating API clients, server stubs, SDKs, and documentation from OpenAPI specifications.

OpenAPI Enforcer

Open-source OpenAPI parser, validator, and request/response enforcement framework.

Prism

Open-source HTTP mock and validation server for OpenAPI specifications, useful for API contract validation and security testing.

oasdiff

Open-source OpenAPI specification diffing tool for detecting breaking changes and API contract differences.

OpenAPI Diff

API specification comparison capabilities useful for identifying undocumented or potentially dangerous API changes during CI/CD.

API Observability & Security Telemetry

OpenTelemetry

Open-source observability framework for collecting API traces, metrics, and logs that can form the telemetry foundation for API security analytics.

Jaeger

Open-source distributed tracing platform useful for investigating API calls, service-to-service communication, and anomalous behavior.

Prometheus

Open-source monitoring and alerting system useful for tracking API traffic, latency, error rates, and security-related metrics.

Grafana

Open-source visualization and observability platform for building API traffic, security, and threat-monitoring dashboards.

Loki

Open-source log aggregation system useful for centralizing API gateway, WAF, authentication, and application-security logs.

WAF & API Protection Components

Coraza WAF

Open-source Web Application Firewall engine compatible with the ModSecurity SecLang rule language and suitable for API/WAF protection.

ModSecurity

Open-source WAF engine capable of inspecting and blocking malicious HTTP traffic in front of APIs and web applications.

OWASP Core Rule Set

Open-source generic WAF rule set for detecting common web and API attack patterns.

Open Policy Agent

Open-source policy engine for expressing and enforcing authorization and security policies across APIs, gateways, microservices, and infrastructure.

Envoy ext_authz

Envoy's external authorization mechanism for delegating API authorization and security decisions to external policy services.

Identity & Authorization Building Blocks

Keycloak

Open-source identity and access management platform supporting OAuth 2.0, OpenID Connect, SAML, identity brokering, and API authorization use cases.

ORY Hydra

Open-source OAuth 2.0 and OpenID Connect server useful for implementing standards-based API authentication and authorization.

ORY Keto

Open-source authorization server based on relationship-based access control concepts, useful for fine-grained API authorization.

Casbin

Open-source authorization library supporting multiple access-control models for applications and APIs.

Additional Strong Open-Source Options

API discovery & inventory — APIClarity, Akto, Kiterunner, HTTPX, Katana, ffuf, OpenTelemetry, and gateway access logs.

API posture management — Akto, APIClarity, Spectral, Optic, oasdiff, and OpenAPI governance pipelines.

API security testing — Schemathesis, RESTler, EvoMaster, OWASP ZAP, Nuclei, Wfuzz, ffuf, and Kiterunner.

API fuzzing — RESTler, Schemathesis, EvoMaster, Wfuzz, ffuf, and custom OpenAPI-driven fuzzers.

Runtime API protection — Apache APISIX, Kong, Tyk, Gravitee, Envoy, Coraza, ModSecurity, and OPA.

API authentication — Keycloak, ORY Hydra, Kong, Apache APISIX, Tyk, Envoy, and OAuth/OIDC tooling.

API authorization — Open Policy Agent, ORY Keto, Casbin, Envoy external authorization, and API gateway policy engines.

API contract security — Spectral, Optic, oasdiff, Prism, OpenAPI Enforcer, and OpenAPI Generator.

API attack-surface mapping — ProjectDiscovery tools, Kiterunner, APIClarity, HTTPX, Katana, and OpenTelemetry.

Security training — OWASP crAPI, OWASP Juice Shop, and deliberately vulnerable API environments.

Observability & detection — OpenTelemetry, Prometheus, Grafana, Jaeger, Loki, and API gateway/WAF telemetry.

Frameworks for building custom systems: Combine APIClarity + OpenTelemetry + Apache APISIX/Kong + Coraza + OPA + Spectral + Schemathesis + Nuclei + Prometheus/Grafana to build a self-hosted API discovery, governance, testing, and runtime-protection platform.

Building a Custom Open-Source API Security Stack

A practical self-hosted API security architecture can be assembled from several layers:

API Discovery — APIClarity, OpenTelemetry, gateway logs, HTTPX, Katana, and Kiterunner.

API Inventory — OpenAPI specifications, APIClarity, gateway telemetry, and custom asset databases.

API Governance — Spectral, Optic, oasdiff, Prism, and OpenAPI Enforcer.

Security Testing — Schemathesis, RESTler, EvoMaster, OWASP ZAP, Nuclei, Wfuzz, and ffuf.

Gateway Enforcement — Apache APISIX, Kong, Tyk, Gravitee, Envoy, or KrakenD.

Runtime Protection — Coraza or ModSecurity with OWASP Core Rule Set.

Authorization — Open Policy Agent, ORY Keto, Casbin, or gateway/Envoy authorization integrations.

Authentication — Keycloak, ORY Hydra, OAuth 2.0, and OpenID Connect.

Telemetry — OpenTelemetry, Prometheus, Grafana, Jaeger, and Loki.

Security Training — OWASP crAPI and OWASP Juice Shop.

This combination provides many of the fundamental capabilities found in commercial API security platforms while retaining control over infrastructure, API traffic, security policies, and sensitive telemetry.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Prefer actively maintained projects with clear documentation and licensing.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Some projects listed under Open-Source are API gateways, WAFs, observability systems, identity platforms, security-testing frameworks, or API-development tools rather than complete API security platforms.

API security tooling should be evaluated against the organization's authentication, authorization, data-protection, compliance, deployment, and threat-model requirements.

Self-hosted open-source solutions require proper hardening, patching, monitoring, secrets management, and operational security.

Only perform security testing against systems you own or are explicitly authorized to assess.

Made for AppSec engineers, API security teams, security researchers, API developers, platform engineers, and organizations building secure API ecosystems.
Let's make API security more open, automated, testable, and developer-friendly.
