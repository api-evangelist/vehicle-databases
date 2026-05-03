# Vehicle Databases (vehicle-databases)
Vehicle Databases provides automotive maintenance schedule APIs with OEM-compliant service schedules for vehicles up to 200,000 miles. Delivers maintenance intervals, service items, fluids, and recall data for automotive service platforms, fleet management systems, and consumer maintenance reminder applications.

**URL:** [https://vehicledatabases.com/vehicle-maintenance-api](https://vehicledatabases.com/vehicle-maintenance-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automotive, Fleet Management, Maintenance, Recalls, Vehicles

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-05-03

## APIs

### Vehicle Databases Maintenance API
The Vehicle Databases Maintenance API delivers OEM-compliant maintenance schedules for vehicles up to 200,000 miles. Provides service intervals by mileage and time, service item descriptions, fluid specifications, part numbers, labor time estimates, recall notices, technical service bulletins, and vehicle decoder (VIN) information for fleet operators, repair shops, and consumer-facing automotive applications.

**Human URL:** [https://vehicledatabases.com/vehicle-maintenance-api](https://vehicledatabases.com/vehicle-maintenance-api)

#### Tags:

 - Automotive, Fleet Management, Maintenance, Recalls, Vehicles

#### Properties

- [Documentation](https://vehicledatabases.com/vehicle-maintenance-api)
- [Portal](https://vehicledatabases.com/)
- [OpenAPI](openapi/vehicle-databases-openapi.yml)
- [JSONSchema - Maintenance Schedule Schema](json-schema/vehicle-databases-maintenance-schedule-schema.json)
- [JSONSchema - Service Item Schema](json-schema/vehicle-databases-service-item-schema.json)
- [JSONSchema - Vehicle Schema](json-schema/vehicle-databases-vehicle-detail-schema.json)
- [JSONStructure - Maintenance Schedule Structure](json-structure/vehicle-databases-maintenance-schedule-structure.json)
- [JSONStructure - Service Item Structure](json-structure/vehicle-databases-service-item-structure.json)
- [Example - Maintenance Schedule Example](examples/vehicle-databases-maintenance-schedule-example.json)
- [Example - Vehicle Example](examples/vehicle-databases-vehicle-detail-example.json)

## Common Properties

- [Website](https://vehicledatabases.com/)
- [Portal](https://vehicledatabases.com/)
- [Documentation](https://vehicledatabases.com/vehicle-maintenance-api)
- [Pricing](https://vehicledatabases.com/pricing)
- [SpectralRules - Vehicle Databases Spectral Rules](rules/vehicle-databases-spectral-rules.yml)
- [Vocabulary - Vehicle Databases Vocabulary](vocabulary/vehicle-databases-vocabulary.yml)
- [NaftikoCapability - Vehicle Maintenance](capabilities/vehicle-maintenance.yaml)

## Features

| Name | Description |
|------|-------------|
| OEM-Compliant Maintenance Schedules | Factory maintenance schedules matching OEM specifications for vehicles up to 200,000 miles with mileage and time-based service intervals. |
| Service Item Details | Detailed service item data including fluid specifications, part numbers, labor time estimates, and OEM-required procedures for each service. |
| VIN Decoder | Decode 17-character VINs to extract make, model, year, engine, trim, and manufacturing details for vehicle identification. |
| Recall Data | NHTSA recall information linked to specific vehicles including recall dates, component affected, risk description, and remedy status. |
| Technical Service Bulletins | OEM technical service bulletins (TSBs) for specific vehicle issues including symptom description, diagnosis, and corrective action. |

## Use Cases

| Name | Description |
|------|-------------|
| Fleet Maintenance Management | Automate maintenance scheduling for commercial and enterprise fleets using OEM-compliant service intervals and mileage-based triggers. |
| Auto Repair Shop Management | Integrate maintenance schedules and TSBs into shop management systems to provide accurate service recommendations and labor estimates. |
| Consumer Maintenance Reminders | Power maintenance reminder apps and connected car services with personalized OEM service schedules based on vehicle and mileage. |
| Insurance Telematics | Combine telematics mileage data with maintenance schedules to provide proactive service alerts in usage-based insurance applications. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Vehicle Databases Maintenance API](openapi/vehicle-databases-openapi.yml)

### JSON Schema

- [vehicle-databases-maintenance-interval-schema.json](json-schema/vehicle-databases-maintenance-interval-schema.json)
- [vehicle-databases-maintenance-schedule-schema.json](json-schema/vehicle-databases-maintenance-schedule-schema.json)
- [vehicle-databases-recall-schema.json](json-schema/vehicle-databases-recall-schema.json)
- [vehicle-databases-service-item-schema.json](json-schema/vehicle-databases-service-item-schema.json)
- [vehicle-databases-tsb-schema.json](json-schema/vehicle-databases-tsb-schema.json)
- [vehicle-databases-vehicle-detail-schema.json](json-schema/vehicle-databases-vehicle-detail-schema.json)

### JSON Structure

- [vehicle-databases-maintenance-interval-structure.json](json-structure/vehicle-databases-maintenance-interval-structure.json)
- [vehicle-databases-maintenance-schedule-structure.json](json-structure/vehicle-databases-maintenance-schedule-structure.json)
- [vehicle-databases-recall-structure.json](json-structure/vehicle-databases-recall-structure.json)
- [vehicle-databases-service-item-structure.json](json-structure/vehicle-databases-service-item-structure.json)
- [vehicle-databases-tsb-structure.json](json-structure/vehicle-databases-tsb-structure.json)
- [vehicle-databases-vehicle-detail-structure.json](json-structure/vehicle-databases-vehicle-detail-structure.json)

### Examples

- [vehicle-databases-maintenance-interval-example.json](examples/vehicle-databases-maintenance-interval-example.json)
- [vehicle-databases-maintenance-schedule-example.json](examples/vehicle-databases-maintenance-schedule-example.json)
- [vehicle-databases-recall-example.json](examples/vehicle-databases-recall-example.json)
- [vehicle-databases-service-item-example.json](examples/vehicle-databases-service-item-example.json)
- [vehicle-databases-tsb-example.json](examples/vehicle-databases-tsb-example.json)
- [vehicle-databases-vehicle-detail-example.json](examples/vehicle-databases-vehicle-detail-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Vehicle Databases Maintenance API](capabilities/shared/vehicle-databases.yaml) — 6 operations for vehicle lookup, VIN decode, maintenance schedules, service items, recalls, and TSBs

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Vehicle Maintenance](capabilities/vehicle-maintenance.yaml) | vehicle-databases | 6 | Fleet Manager, Service Advisor, Vehicle Owner |

## Vocabulary

- [Vehicle Databases Vocabulary](vocabulary/vehicle-databases-vocabulary.yml) — Unified taxonomy mapping 5 resources, 4 actions, 1 workflow, and 3 personas across vehicle identification, maintenance planning, and safety compliance dimensions

## Rules

- [Vehicle Databases Spectral Rules](rules/vehicle-databases-spectral-rules.yml) — 20 rules across 9 categories enforcing Vehicle Databases API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
