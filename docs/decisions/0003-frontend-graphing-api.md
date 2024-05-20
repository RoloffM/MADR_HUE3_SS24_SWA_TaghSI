---
# Another example for metadata
parent: Decisions
nav_order: 100
title: ADR 0003: Frontend Graphing API (URL-based)

# status: accepted
# date: 2024-05-20
# deciders: Sina Taghavi
# consulted: Graphite Development Team
# informed: Graphite Users
---
# Frontend Graphing API (URL-based)

## Context and Problem Statement

Graphite needs an intuitive and flexible method for users to request and customize graphs.

## Decision Drivers

* Ease of use
* Flexibility in graph customization
* Integration simplicity

## Considered Options

* URL-based API
* RPC-based API
* Custom frontend application

## Decision Outcome

Chosen option: "URL-based API", because it offers simplicity and ease of integration, allowing users to customize graphs via query parameters in URLs.

### Consequences

* Good, because easy for users to understand and use; straightforward integration with other web technologies.
* Bad, because limited flexibility for very complex graphing needs.

## Validation

The choice was validated through user testing and feedback, ensuring that the URL-based API met the needs for ease of use and flexibility.

## Pros and Cons of the Options

### URL-based API

* Good, because intuitive and easy to use.
* Good, because simple integration with other web technologies.
* Bad, because limited flexibility for complex graphing needs.

### RPC-based API

* Good, because highly flexible and powerful.
* Good, because allows complex interactions.
* Bad, because more complex and harder to use for simple tasks.
* Bad, because more difficult to integrate with simple web technologies.

### Custom frontend application

* Good, because tailored to specific needs.
* Good, because highly flexible and powerful.
* Bad, because high development and maintenance cost.
* Bad, because potential for overcomplication and user resistance to learning a new system.

## More Information

For more details on the decision process, see the user feedback reports and integration case studies.
