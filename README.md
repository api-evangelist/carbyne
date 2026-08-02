# Carbyne

Carbyne is a cloud-native mission-critical contact center and emergency communications company whose platform — sold as Axon 911 Core and Carbyne APEX — powers 9-1-1, 3-1-1 and non-emergency call handling for Public Safety Answering Points (PSAPs), enterprises, and transportation, education and GSOC operators. The platform delivers caller device location, live video, audio streaming, Text-to-911, AI transcription and real-time translation, emergency call triage, wallboards, analytics and event history to telecommunicators, and integrates with CAD, ESInet, voice recorders, PBX, mapping and IoT systems through a contract-gated open API. Founded in 2015 in Tel Aviv and New York as Reporty Homeland Security, Carbyne was acquired by Axon Enterprise in 2025.

- Website: https://carbyne.com/
- Cloud Security & compliance: https://carbyne.com/cloud-advantage/cloud-security/
- Integrations: https://carbyne.com/cloud-advantage/carbyne-integrations/
- API Terms of Use: https://carbyne.com/wp-content/uploads/2023/03/Carbyne-API-Terms-of-Use.final_.3.23.23.pdf
- GitHub: https://github.com/carbyne911

## API surface

Carbyne markets an open API and publishes API Terms of Use, but as of 2026-08-02 it publishes **no public machine-readable API contract** — no OpenAPI, GraphQL, AsyncAPI, gRPC, MCP server or A2A agent card — and no public developer portal, API reference or SDK. API access is granted to contracted customers and partners. The full discovery log, including hosts rejected as catch-all false positives, is in `well-known/carbyne-well-known.yml`.

## Artifacts

| Directory | File | Method |
|---|---|---|
| `authentication/` | `carbyne-authentication.yml` | searched |
| `conformance/` | `carbyne-conformance.yml` | searched |
| `lifecycle/` | `carbyne-lifecycle.yml` | searched |
| `packages/` | `carbyne-packages.yml` | searched |
| `security/` | `carbyne-domain-security.yml` | probed |
| `security/` | `carbyne-trust-center.yml` | searched |
| `well-known/` | `carbyne-well-known.yml` | probed |
| `llms/` | `carbyne-llms.txt` | generated |
