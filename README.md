![](screenshots/xsoarlogo.PNG)

## Use Case Definition

This document provides a template for defining a use case to be implemented in XSOAR. The Use Case is defined by the process, logic, and tasks that are being done as part of an Incident Response process for a specific incident type.

### Use Case Name

Case00-

### Use Case Description

### Trigger

The playbook is triggered when an a condition is met <condition>.

OR

The playbook is meant to run as a scheduled job <timeframe>.

### Incident structure and mapping

**Layout:** Name of the layout

**Incident Type:** Type of the incident

**Playbook:** Name of the playbook

### Incident response process

Description of the playbook flow as consecutive points.

### Enrichment

Description of how data was enriched throughout the incident life cycle.

### Manual Steps

Description of any manual steps in the playbook if any exist.

### End-user interactiveness

Description of any user interaction ex:through email, messaging app, links, forms...

### Assumptions

List of assumptions the logic of the playbook follows.

- The structure of the data
- The accuracy of the input
- Critical tasks to be successful

### Deduplication logic

In case incidents were linked, this is a description of the deduplication of linked incidents.

## Playbook

- <Playbook Name>

<Screenshot of playbook>

## Subplaybooks

- <Subplaybook1 Name>

<Screenshot of playbook>

- <Subplaybook2 Name>

<Screenshot of playbook>

## Testing

- Description of the test case(s)

- Proof of playbook running successfully

## 3rd Party Integrations

| Product Category | Product name and version | Actions needed |
| --- | --- | --- |
|  |  |  |

## Incident Structure (Custom Field)

| Field name | Field name | Comments and Values | Layout Placement |
| --- | --- | --- | --- |
| Sender Email | Short Text |  | New / Edit / Close / Summary |
