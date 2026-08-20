🎸 Tone Lord API Specification

Welcome to the Tone Lord API — the ultimate, slightly arrogant REST API contract designed for bedroom shredders and true tone chasers who traded heavy, expensive tube amplifiers for digital bedroom perfection.

Yes, it is fictional.
Yes, the tone is intentionally overconfident.
And yes, someone had to document the guitar plugins.

This project is a Technical Writing portfolio case focused on creating developer-facing API documentation from an OpenAPI specification.

🔗 Live Documentation

👉 View the interactive API documentation on Bump.sh

🎯 Project Goals

The goal was to create clear, usable API documentation that allows a developer to:

* understand what the API provides;
* authenticate with the API;
* discover available endpoints;
* understand request parameters and schemas;
* construct API requests;
* interpret responses and error codes.

The project also explores how a consistent information structure and a deliberate tone of voice can coexist in developer documentation.

🛠️ Tools & Standards

* OpenAPI 3.0.3 (OAS3)
* YAML
* REST API
* Git / GitHub
* Bump.sh
* API-first / design-first approach

📖 API Overview

Tone Lord API provides a catalog of guitar VST/AU plugins and audio effects.

The specification includes endpoints for:

* retrieving the plugin catalog (GET /plugins);
* viewing an individual plugin (GET /plugins/{id});
* adding new plugins (POST /plugins);
* filtering the catalog by manufacturer or category.

The data model includes nested objects representing virtual amplifiers, cabinets, and stompboxes.

🔐 Authentication & Permissions

The API uses a simulated Bearer Token (JWT) authentication model.

Public users can access read-only operations, while write operations require an administrator token.

The documentation also describes common error responses, including:

* 401 Unauthorized
* 403 Forbidden
* 404 Not Found

✍️ Documentation Approach

This project focuses on more than describing endpoints.

The documentation was structured around the needs of the intended audience: developers who need to understand the API quickly and use it correctly.

Key considerations included:

* task-oriented information structure;
* consistent terminology;
* clear request and response descriptions;
* explicit authentication requirements;
* documented error cases;
* examples and schemas where they provide useful context;
* balancing technical clarity with a deliberately informal tone of voice.

🎸 Tone of Voice

The API is fictional, so I used it as an opportunity to experiment with tone of voice in developer documentation.

The subject matter is intentionally playful and slightly ridiculous, but the documentation itself remains structured and technically oriented.

The idea is simple:

The API can take itself seriously. The documentation doesn’t always have to.

📌 Disclaimer

This is an independent portfolio project created for educational and demonstration purposes.

The Tone Lord API is fictional and is not affiliated with any real company, product, or service.

Documentation goals

* Provide a clear overview of the API and its resources.
* Make endpoints easy to discover and understand.
* Document authentication and authorization requirements.
* Provide request parameters, response schemas, and error responses.
* Publish the specification as interactive API documentation.

What I did

* Designed the information structure of the API reference.
* Created an OpenAPI 3.0.3 specification in YAML.
* Defined endpoints, parameters, schemas, authentication, and error responses.
* Added examples and descriptions for API consumers.
* Published the documentation using Bump.sh.
* Reviewed the documentation for consistency and usability.
