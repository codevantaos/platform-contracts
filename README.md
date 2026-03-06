# Platform Contracts

This repository defines the standardized API contracts for the AutoEcoOps platform. It includes OpenAPI specifications for REST APIs, AsyncAPI specifications for event-driven architectures, and JSON Schemas for configuration validation.

## Contents

- `openapi/`: Contains OpenAPI (Swagger) specifications for synchronous RESTful APIs.
- `asyncapi/`: Contains AsyncAPI specifications for asynchronous event-driven APIs.
- `json-schema/`: Contains JSON Schemas for validating various configuration files and data structures.

## Usage

These contracts serve as the single source of truth for inter-service communication and data exchange within the AutoEcoOps ecosystem. Developers should always refer to these specifications when building or integrating services.

## Versioning

API versions are managed within their respective specification files. Breaking changes will result in a new major version.
