# Bird (bird-com)

Bird (formerly MessageBird) is an omnichannel CRM for marketing, service, and payments. Its REST APIs at https://api.bird.com let businesses send and receive messages across SMS, WhatsApp, email, and voice through a unified Channels and Conversations interface, manage contacts and phone numbers, and migrate from the legacy MessageBird REST API at https://rest.messagebird.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bird-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bird-com/refs/heads/main/apis.yml)

> Note: Bird was formerly known as MessageBird. The current platform APIs live at `api.bird.com` (AccessKey auth); the predecessor MessageBird REST API remains documented at `rest.messagebird.com`. Not to be confused with Bird (the e-scooter company) or Birdeye (the reputation/reviews platform).

## Tags

- CRM
- Messaging
- SMS
- WhatsApp
- Email
- Voice
- Omnichannel
- CPaaS

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Bird Channels / Messaging API

Send and receive messages across SMS, WhatsApp, email, and other channels through a single unified workspace/channel interface, with channel management, connectors, and presigned media uploads.

- **Human URL:** [https://docs.bird.com/api/channels-api](https://docs.bird.com/api/channels-api)
- **Base URL:** `https://api.bird.com`

#### Tags

- Channels
- Messaging
- SMS
- WhatsApp
- Email

#### Properties

- [Documentation](https://docs.bird.com/api/channels-api)
- [API Reference](https://docs.bird.com/api/channels-api/api-reference/messaging)
- [OpenAPI](openapi/bird-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bird-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bird-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bird Contacts API

Manage contact records, identifiers, attributes, suppressions, and lists within a workspace - the CRM data layer behind Bird's messaging channels.

- **Human URL:** [https://docs.bird.com/api/contacts-api](https://docs.bird.com/api/contacts-api)
- **Base URL:** `https://api.bird.com`

#### Tags

- Contacts
- CRM
- Lists

#### Properties

- [Documentation](https://docs.bird.com/api/contacts-api)
- [API Reference](https://docs.bird.com/api/contacts-api/api-reference/manage-workspace-contacts)
- [OpenAPI](openapi/bird-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bird-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bird-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bird Conversations API

Create and manage threaded conversations that unify omnichannel messaging into a centralized inbox, sending and retrieving messages scoped to a conversation.

- **Human URL:** [https://docs.bird.com/api/conversations-api](https://docs.bird.com/api/conversations-api)
- **Base URL:** `https://api.bird.com`

#### Tags

- Conversations
- Omnichannel
- Inbox

#### Properties

- [Documentation](https://docs.bird.com/api/quickstarts/conversations)
- [API Reference](https://docs.bird.com/api/conversations-api/api-reference/conversations-messaging/get-conversation-message)
- [OpenAPI](openapi/bird-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bird-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bird-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bird Numbers API

Discover, purchase, and manage long-code, short-code, and alphanumeric sender phone numbers assigned to a workspace, plus network/country number lookup.

- **Human URL:** [https://docs.bird.com/api/numbers-api](https://docs.bird.com/api/numbers-api)
- **Base URL:** `https://api.bird.com`

#### Tags

- Numbers
- Phone Numbers
- Lookup

#### Properties

- [Documentation](https://docs.bird.com/api/numbers-api)
- [API Reference](https://docs.bird.com/api/numbers-api/api-reference/list-your-numbers)
- [OpenAPI](openapi/bird-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bird-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bird-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Legacy MessageBird REST API

The predecessor MessageBird REST API at rest.messagebird.com covering SMS messages, voice messaging, Verify (one-time passwords), and Lookup (HLR / number validation), still documented for existing integrations.

- **Human URL:** [https://developers.messagebird.com/api/](https://developers.messagebird.com/api/)
- **Base URL:** `https://rest.messagebird.com`

#### Tags

- Legacy
- MessageBird
- SMS
- Voice
- Verify
- Lookup

#### Properties

- [Documentation](https://developers.messagebird.com/api/)
- [API Reference](https://developers.messagebird.com/api/sms-messaging/)
- [OpenAPI](openapi/bird-com-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/messagebird)
- [LinkedIn](https://www.linkedin.com/company/bird)
- [Website](https://bird.com/)
- [Documentation](https://docs.bird.com/)
- [Plans](plans/bird-com-plans-pricing.yml)
- [Rate Limits](rate-limits/bird-com-rate-limits.yml)
- [Fin Ops](finops/bird-com-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
