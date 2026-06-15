# Pinata (pinata)

Pinata is an IPFS pinning and dedicated-gateway provider with a Files API, IPFS Pinning Service API, dedicated Gateways, Groups, and Workspaces. Built around IPFS CIDs with JWT-authenticated REST APIs and an SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pinata/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pinata/refs/heads/main/apis.yml)

## Tags

- Web3
- IPFS
- Storage
- Gateway

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Pinata Files API

REST API for uploading, listing, organizing, and deleting files pinned to IPFS or stored privately. Supports public and private (Submarine) modes, signed URLs, and Groups.

- **Human URL:** [https://docs.pinata.cloud/api-reference/endpoint/upload-a-file](https://docs.pinata.cloud/api-reference/endpoint/upload-a-file)
- **Base URL:** `https://api.pinata.cloud/v3`

#### Tags

- REST
- IPFS
- Files

#### Properties

- [Documentation](https://docs.pinata.cloud/api-reference)
- [Postman Collection](collections/pinata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pinata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pinata IPFS Pinning Service API

Implementation of the IPFS Pinning Service API standard for compatibility with go-ipfs / kubo and js-ipfs clients.

- **Human URL:** [https://docs.pinata.cloud/api-reference/endpoint/ipfs-pinning-service-api](https://docs.pinata.cloud/api-reference/endpoint/ipfs-pinning-service-api)
- **Base URL:** `https://api.pinata.cloud/psa`

#### Tags

- REST
- IPFS
- Pinning Service

#### Properties

- [Documentation](https://docs.pinata.cloud/api-reference/endpoint/ipfs-pinning-service-api)
- [Postman Collection](collections/pinata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pinata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pinata Dedicated Gateway

Dedicated IPFS HTTP gateway endpoint per account for content retrieval with custom subdomain, access controls, and analytics.

- **Human URL:** [https://docs.pinata.cloud/gateways/dedicated-ipfs-gateways](https://docs.pinata.cloud/gateways/dedicated-ipfs-gateways)
- **Base URL:** `https://{your-gateway}.mypinata.cloud`

#### Tags

- HTTP
- Gateway

#### Properties

- [Documentation](https://docs.pinata.cloud/gateways/dedicated-ipfs-gateways)
- [Postman Collection](collections/pinata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pinata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pinata Groups API

REST API for organizing CIDs into named Groups with bulk add/remove operations.

- **Human URL:** [https://docs.pinata.cloud/api-reference/endpoint/v3-create-a-public-group](https://docs.pinata.cloud/api-reference/endpoint/v3-create-a-public-group)
- **Base URL:** `https://api.pinata.cloud/v3`

#### Tags

- REST
- Groups

#### Properties

- [Documentation](https://docs.pinata.cloud/api-reference/endpoint/v3-create-a-public-group)
- [Postman Collection](collections/pinata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pinata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/PinataCloud)
- [LinkedIn](https://www.linkedin.com/company/pinatacloud)
- [Website](https://pinata.cloud/)
- [Plans](plans/pinata-plans-pricing.yml)
- [Rate Limits](rate-limits/pinata-rate-limits.yml)
- [Fin Ops](finops/pinata-finops.yml)
- [L L Ms Txt](https://docs.pinata.cloud/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
