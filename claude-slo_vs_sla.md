# SLO vs SLA (Structured Notes)

## 1. Introduction

In IT service management and cloud computing, organizations define
measurable targets to maintain **service reliability and performance**.
Two important concepts used for this purpose are:

-   **SLO -- Service Level Objective**
-   **SLA -- Service Level Agreement**

Both help ensure that services meet expected performance standards and
customer expectations.

------------------------------------------------------------------------

# 2. Service Level Objective (SLO)

## Definition

A **Service Level Objective (SLO)** is a **specific and measurable
target set by an organization for service performance**.

It defines the **desired level of reliability or performance** that the
service should achieve.

## Characteristics

-   Internal performance target
-   Used by engineering and operations teams
-   Helps monitor and improve service reliability
-   Usually expressed using measurable metrics

## Common Metrics Used in SLO

-   **Availability** -- Percentage of time the service is accessible
-   **Latency** -- Response time of the system
-   **Error Rate** -- Number of failed requests

## Example

A company may define the following SLO:

-   Website availability must be **99.9% per month**.

This means the system should remain available almost all the time with
minimal downtime.

------------------------------------------------------------------------

# 3. Service Level Agreement (SLA)

## Definition

A **Service Level Agreement (SLA)** is a **formal contract between the
service provider and the customer**.

It defines the **guaranteed level of service** that must be provided.

## Characteristics

-   External agreement
-   Legally binding contract
-   Defines service commitments
-   Includes penalties or compensation if the service level is not
    achieved

## Example

An SLA may include conditions such as:

-   Service availability guaranteed: **99.5% uptime**
-   If uptime drops below 99.5%, customers receive **service credits or
    compensation**.

------------------------------------------------------------------------

# 4. Key Differences Between SLO and SLA

  -----------------------------------------------------------------------
  Feature                 SLO                     SLA
  ----------------------- ----------------------- -----------------------
  Full Form               Service Level Objective Service Level Agreement

  Type                    Internal performance    External contractual
                          target                  agreement

  Audience                Engineering /           Customers and service
                          Operations teams        providers

  Purpose                 Maintain service        Define customer
                          reliability             expectations

  Penalty                 No direct penalty       Includes penalties or
                                                  compensation

  Scope                   Technical performance   Business-level
                          goals                   commitments
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 5. Relationship Between SLO and SLA

SLO and SLA are closely related but serve different purposes.

-   **SLOs are internal goals used by organizations to maintain service
    performance.**
-   **SLAs are promises made to customers regarding service quality.**
-   Organizations usually set **SLO stricter than SLA** to ensure they
    always meet customer commitments.

### Example

  Metric Type   Example Value
  ------------- --------------------------------------
  SLO           99.9% uptime target set internally
  SLA           99.5% uptime guaranteed to customers

This ensures the organization has a buffer to maintain service
reliability.

------------------------------------------------------------------------

# 6. Practical Example

Consider a **cloud storage service provider**.

### SLO

-   Internal goal: **99.9% service availability per month**.

### SLA

-   Customer guarantee: **99.5% uptime**.
-   If uptime falls below 99.5%, customers receive **service credits**.

------------------------------------------------------------------------

# 7. Summary

-   **SLO (Service Level Objective)** defines the internal performance
    target for a service.
-   **SLA (Service Level Agreement)** is a contractual commitment made
    to customers.
-   Organizations maintain **higher SLO targets to ensure SLA
    requirements are met**.

Both concepts help organizations deliver **reliable and high-quality
services**.
