# Google Business Messages API

The Google Business Messages API enables agents to send messages, create events, and manage customer satisfaction surveys within conversations. It allows businesses to communicate with customers directly through Google entry points such as Search and Maps.

## APIs

- **Google Business Messages API** - Send messages, create events, update receipts, and manage surveys in business conversations.

## Base URL

```
https://businessmessages.googleapis.com/v1
```

## Key Endpoints

- **Create Message** - `POST /conversations/{conversationId}/messages` - Send a message
- **Update Receipt** - `PATCH /conversations/{conversationId}/messages/{messageId}:receiptUpdate` - Send a read receipt
- **Create Event** - `POST /conversations/{conversationId}/events` - Create a conversation event
- **Create Survey** - `POST /conversations/{conversationId}/surveys` - Create a satisfaction survey

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/Message.json) - JSON Schema (draft 2020-12) for Message
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://developers.google.com/business-communications/business-messages/guides)
- [API Reference](https://developers.google.com/business-communications/business-messages/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
