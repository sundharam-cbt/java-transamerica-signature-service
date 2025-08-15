**Java Transamerica Signature Service**

Java Transamerica Signature Service is a public-facing wrapper service for handling digital signatures of clients, agents, and other stakeholders (Payor, PI, Owner). It provides a unified interface to access signature operations without IP or VPN restrictions.

**Overview**

This service acts as a gateway that redirects incoming API requests to the respective backend services. It does not implement business logic itself; instead, it simplifies external integrations by providing a consistent and secure entry point for all signature-related operations.

**Key Features**

- Public access for clients, agents, and payors without IP/VPN restrictions.

- Serves as a wrapper/gateway for backend signature services.

- Unified and consistent interface for all signature operations.

- Securely routes API requests to the appropriate backend.

**API Structure**

All APIs are exposed publicly and internally routed to their corresponding backend services. The service ensures that requests are handled efficiently and securely without exposing backend implementation details.

**Usage**

External systems or clients can call the service APIs to perform signature operations. The service forwards the request to the correct backend service and returns the response seamlessly.
