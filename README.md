# deutsche-telekom

Deutsche Telekom — Europe's largest telecommunications operator (Bonn, Germany), parent of T-Mobile US and T-Systems.

## Developer Surface

- **Developer Portal:** https://developer.telekom.com/en
- **API Portal:** https://developer.telekom.com/en/api-portal
- **Products:** https://developer.telekom.com/en/products
- **GitHub:** https://github.com/telekom
- **Open Telekom Cloud:** https://www.open-telekom-cloud.com/en (docs: https://docs.otc.t-systems.com/)

## API Portfolio

### MagentaBusiness CPaaS (with Vonage)
- SMS API
- Rich Communication Services (RCS)
- Conversational Connect
- Voice API
- Video API
- Reports API
- AI Studio

### Network APIs (GSMA Open Gateway / CAMARA)
- Number Verification (silent mobile-number verification)
- Verify API (multi-channel 2FA)
- 5G Slices for App Developers

### Open Telekom Cloud (T-Systems)
- Compute, storage, networking, database, container, AI, and API Gateway services with full REST APIs (OpenStack-based, GAIA-X aligned)

### TARDIS Control Plane (open source — OpenAPI 3)
- Rover API
- Controlplane API
- Identity API
- Discovery (Application, Event, Stargate)
- File Manager API
- Secret Manager API

### Open Source Ecosystem
- Open Telekom Integration Platform (O28M) — Kong-based API gateway with Jumper sidecar and Keycloak identity
- Horizon pub/sub ecosystem (Galaxy, Comet, Quasar, Vortex, Cosmoparrot, Golaris)
- Scale design system, Sparrow monitoring, K8s-Breakglass, Das-Schiff network operator, Wurzel RAG ETL

## Artifacts in this repo

- `apis.yml` — APIs.json catalog entry
- `openapi/` — Downloaded OpenAPI 3 specs from `telekom/controlplane` (TARDIS internal developer platform)
