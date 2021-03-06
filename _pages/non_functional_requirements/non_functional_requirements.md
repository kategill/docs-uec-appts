---
title: Non-Functional Requirements (Care Connect)
toc: True
sidebar: overview_sidebar
permalink: non_functional_requirements.html
summary: "Details of non-functional requirements (NFRs) that describe system attributes such as security, reliability, maintainability, scalability, and usability"
---

The non-functional requirements for systems assured for UEC Appointment booking using the Care Connect specification are detailed here.
For the equivalent requirements for booking using the GP Connect standard, please see here: <a href="https://nhsconnect.github.io/gpconnect/development_api_non_functional_requirements.html" target="_blank">GP Connect non-functional requirements</a>.

## Security 
Provider systems SHALL resist unauthorized, accidental or unintended usage and provide access only to legitimate users. 

## Volume and performance 
  * Volumetric
    * Provider systems MUST meet the agreed volumetric performance targets.
   
  * Performance
    * Provider systems MUST meet the agreed response time performance targets.
    
## Capacity 
Provider systems MUST meet the agreed capacity requirements. 

## Scalability 
Provider systems SHALL be designed to accommodate increased volumes, workloads and users. 

## Availability 
Provider systems SHALL meet the agreed availability targets (service time and/or hours and planned downtime).

## Recoverability 
Provider systems SHALL meet the agreed recoverability targets

## Audit & provenance 
Provider systems SHALL audit all API access and actions. 

## Maintainability 
Provider systems SHALL be designed to optimise the ability of maintenance personnel to revise or enhance it. 

## Serviceability 
Provider systems SHALL be designed so that technical support personnel are able to monitor and manage it in operation. In particular error messages presented to the end user MUST be clear, understandable and helpful.

## Clinical Risk Management
Provider and consumer systems SHALL comply with NHS Digital <a href="https://digital.nhs.uk/services/solution-assurance/the-clinical-safety-team/clinical-risk-management-standards" target="_blank">Clinical Risk Management Standards</a>, in particular DCB0160.

## Data retention 
Provider systems SHALL retain data in line with existing relevant Informational Governance and data protection regulation. 

## Usability 
Provider and consumer systems SHOULD follow the <a href="https://www.iso.org/standard/21197.html" target="_blank">ISO 13407</a> / <a href="https://www.iso.org/standard/52075.html" target="_blank">ISO 9241-210</a> 

## Accessibility 
Provider and consumer systems MUST maintain a compliance of minimum Double “A” of the WCAG 1.0 (or equivalent in WCAG 2.0) or, as stipulated by UK Government guidelines, for all user interfaces. Please see the ,<a href="https://www.w3.org/WAI/" target="_blank">Web Accessibility Initiative</a> for more details. 
