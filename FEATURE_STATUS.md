# Feature status — Logistics, warehouse & transport

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 565 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 1 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 1 | 0 | Native records/view |
| Reports & analytics | report | 22 | 0 | Native records/view |
| Activity & audit trail | audit | 22 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| 3PL contract and rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility and account registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory snapshot ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Receipt and putaway reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage position recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pick pack and handling audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Value-added service validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum commitment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory accuracy SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order cutoff and fulfillment SLA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loss and damage claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| 3PL dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Facility SKU and activity analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Airline forwarder contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Air waybill ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Actual weight validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dimensional weight calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chargeable weight calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base rate reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security surcharge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel surcharge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Screening fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Handling fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum charge calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Routing service validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice matching | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier lane analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bonded facility registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warehouse entry ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory receipt control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lot serial traceability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Manipulation tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Withdrawal for consumption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export withdrawal control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Destruction evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Five-year deadline monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duty liability calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bond sufficiency monitoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CBP report reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory discrepancy workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duty payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility inventory analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility zone registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lot pallet ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily inventory reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pallet-day calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Minimum capacity validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Blast freezing charge | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inbound handling audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outbound handling audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Temperature excursion credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy surcharge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Facility product analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drayage contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Container booking registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Port rail event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointment evidence | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Base drayage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chassis day reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Split charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flip charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pre-pull audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage yard charge control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overweight permit validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Toll fuel audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Failed attempt responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Port carrier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Card driver and vehicle registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Telematics and odometer matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Impossible transaction detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel volume and tank-capacity control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel grade and product validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price and discount audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Toll transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate and impossible toll detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rental and replacement vehicle control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud case workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor dispute and recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Card control and preventive alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vehicle vendor and route analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zone and activation registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Part and HTS classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foreign and domestic status | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Admission transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inventory control reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Zone-to-zone transfer management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Production BOM consumption | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Privileged status control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inverted-tariff savings calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duty deferral calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scrap and waste treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export and destruction relief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entry and withdrawal preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CBP discrepancy workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| FTZ annual report preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duty savings and compliance analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipment container registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rail event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Terminal event timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Free-time calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Storage charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lift charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chassis responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flip split validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drayage linkage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider dispute package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Terminal provider analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Origin-destination rate matrix | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Container and equipment registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Booking ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bill-of-lading ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Base ocean rate reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bunker adjustment validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Peak-season surcharge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| General rate increase control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MQC tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Origin charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Destination charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier dispute generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lane and equipment analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Serialized pooled registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipment transfer ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trading partner balances | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Daily hire calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lost asset validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repair damage fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer rejection workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Depot receipt reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Unreturned asset alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer recovery billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Provider dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Asset recovery ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network cycle analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier contract and rate-card library | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Shipment manifest ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Invoice and EDI ingestion | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Base-rate recalculation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| DIM-weight validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Accessorial charge validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Fuel-surcharge audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Duplicate invoice detection | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Late-delivery guarantee recovery | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Address-correction validation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| LTL class and density audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Minimum-charge and discount audit | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Carrier dispute packet generation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Credit and refund reconciliation | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Carrier lane and leakage analytics | records | 1 | 1 | AI question-and-answer workspace; records available as context |
| Terminal tariff library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Booking container registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gate event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lift move validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wharfage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reefer power duration | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazardous cargo fee | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Overweight handling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customs exam charge | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Empty return treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Terminal dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Port charge analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor return-policy library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return authorization registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SKU and serial tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return shipment generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier delivery evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor receipt confirmation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expected credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Restocking fee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warranty credit validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Core and deposit recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing-credit detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor inquiry workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit memo matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| General-ledger reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor and SKU recovery analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Package manifest ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tracking event timeline | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service commitment calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery timestamp validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Late delivery detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exception code validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather waiver review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Peak waiver control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Address correction audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund eligibility calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier refund submission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Denial appeal workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit invoice reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier service analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product master ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| HTS classification review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Binding ruling library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country-of-origin analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Substantial transformation test | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trade agreement qualification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Section 301 exclusion mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Entry line ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duty recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post-summary correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Protest deadline control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prior disclosure coordination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund evidence package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customs response tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product origin analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier broker agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lane rate registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tender load ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract versus spot determination | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Linehaul recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel index validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mileage calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stop-off charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Layover validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detention validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lumper evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| TONU validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lane carrier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Map | records | 1 | 0 | Native records/view |
| Vehicles | records | 3 | 0 | Native records/view |
| Drivers | records | 3 | 0 | Native records/view |
| Routes | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Fuel | records | 4 | 0 | Native records/view |
| Safety | records | 1 | 0 | Native records/view |
| Trips | records | 2 | 0 | Native records/view |
| Maintenance | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Alerts | records | 4 | 0 | Native records/view |
| Geofences | records | 1 | 0 | Native records/view |
| Insights | records | 2 | 0 | Native records/view |
| Carbon | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance trends | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost per mile | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet utilization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leaderboard | records | 1 | 0 | Native records/view |
| Route optimization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Fuel analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predictive maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Route recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver coaching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel waste | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Breakdown prevention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Load balancer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver wellness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel fraud | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver burnout | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost per mile report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Eld hours violation monitor | records | 1 | 0 | Native records/view |
| Vehicle Models | records | 1 | 0 | Native records/view |
| Sensor Configurations | records | 1 | 0 | Native records/view |
| Driving Scenarios | records | 1 | 0 | Native records/view |
| Training Sessions | records | 1 | 0 | Native records/view |
| Simulation Results | records | 1 | 0 | Native records/view |
| Route Planning | records | 2 | 0 | Native records/view |
| Object Detection | records | 1 | 0 | Native records/view |
| Traffic Simulation | records | 1 | 0 | Native records/view |
| Weather Simulation | records | 1 | 0 | Native records/view |
| Safety Metrics | records | 1 | 0 | Native records/view |
| Fleet Management | records | 2 | 0 | Native records/view |
| Map Environments | records | 1 | 0 | Native records/view |
| AI Models | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Collision Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Compliance | records | 1 | 0 | Native records/view |
| ODD Coverage Matrix | records | 1 | 0 | Native records/view |
| Favorites | records | 1 | 0 | Native records/view |
| Simulation runs | records | 1 | 0 | Native records/view |
| Scenario comparison | records | 1 | 0 | Native records/view |
| Compliance pathway | records | 1 | 0 | Native records/view |
| Safety metrics dashboard | records | 1 | 0 | Native records/view |
| Scenario safety | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Temperature Monitoring | records | 1 | 0 | Native records/view |
| Spoilage Predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| FDA/HACCP Compliance | records | 4 | 0 | Native records/view |
| Carrier Scoring | records | 2 | 0 | Native records/view |
| Incident Documentation | records | 4 | 0 | Native records/view |
| Facilities (Multi-Site) | records | 1 | 0 | Native records/view |
| Regulatory Changes | records | 1 | 0 | Native records/view |
| Predictive Ops | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lot Recall Trace | records | 1 | 0 | Native records/view |
| User Management | records | 1 | 0 | Native records/view |
| Export Controls | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Country Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Landed Cost Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker Instruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Classify | records | 1 | 0 | Native records/view |
| Screen | records | 1 | 0 | Native records/view |
| Trade tools | records | 1 | 0 | Native records/view |
| Ftz reconciliation | records | 1 | 0 | Native records/view |
| Tariff compliance optimization | records | 1 | 0 | Native records/view |
| Supply chain visibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Automation of declarations | records | 1 | 0 | Native records/view |
| Sanctions screening agent | records | 1 | 0 | Native records/view |
| Duties lacks ai tariff optimization endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shipments lacks ai delay prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sanctions lacks ai risk screening agent | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Documents lacks ai declaration auto generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No webhooks for carrier or government api pushes | integration | 1 | 0 | Provider request records only |
| No sms push notifications | records | 1 | 0 | Native records/view |
| No payment duty collection workflow | records | 1 | 0 | Native records/view |
| No calendar scheduling | records | 1 | 0 | Native records/view |
| No mobile api surface | records | 1 | 0 | Native records/view |
| Charging Stations | records | 1 | 0 | Native records/view |
| Cost Analysis | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Battery Health | records | 1 | 0 | Native records/view |
| Energy Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Charger Queue Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transition Plans | records | 1 | 0 | Native records/view |
| Carbon Footprint | records | 1 | 0 | Native records/view |
| Driver Assignment | records | 1 | 0 | Native records/view |
| Budget Planner | records | 1 | 0 | Native records/view |
| Trip Planner | records | 1 | 0 | Native records/view |
| Parts | records | 1 | 0 | Native records/view |
| Work Orders | records | 1 | 0 | Native records/view |
| Assignments | records | 1 | 0 | Native records/view |
| Downtime | records | 1 | 0 | Native records/view |
| Scheduling | records | 1 | 0 | Native records/view |
| Costs | records | 1 | 0 | Native records/view |
| Tires | records | 1 | 0 | Native records/view |
| Tire Rotation | records | 1 | 0 | Native records/view |
| Inspections | records | 2 | 0 | Native records/view |
| Warranties | records | 1 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| Fleet Overview | records | 1 | 0 | Native records/view |
| Dynamic Rate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier Capacity Forecast | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lane Profitability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mode Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spot Market Scan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detention & Demurrage Predictor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Damage Vision Assessor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent Quote | records | 1 | 0 | Native records/view |
| AI Pricing Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Results | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Lane Elasticity | records | 1 | 0 | Native records/view |
| Renewal Alerts | records | 1 | 0 | Native records/view |
| Backlog Tools | records | 1 | 0 | Native records/view |
| Agentic Spot-Market Trading Agent | records | 1 | 0 | Native records/view |
| Multimodal Optimization Solver | records | 1 | 0 | Native records/view |
| Carrier Compliance + Sustainability Tracking | records | 1 | 0 | Native records/view |
| Supply Chain Finance Integration | integration | 1 | 0 | Provider request records only |
| Customer Demand Forecasting + Lane Capacity | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vision-Based Damage Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic Rate Calculator Gap | records | 1 | 0 | Native records/view |
| Contract Optimization Recommender Gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection On Shipment Patterns Gap | records | 1 | 0 | Native records/view |
| Lane Profitability Analyzer Gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mode Recommendation Gap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notifications Gap | records | 1 | 0 | Native records/view |
| Webhook Receivers/Dispatchers Gap | integration | 1 | 0 | Provider request records only |
| Carrier Performance Scorecard Gap | records | 1 | 0 | Native records/view |
| Exception/Claim Management Gap | records | 1 | 0 | Native records/view |
| Real-Time Shipment Tracking Gap | records | 1 | 0 | Native records/view |
| Rate Quotes | records | 1 | 0 | Native records/view |
| Shipments | records | 2 | 0 | Native records/view |
| Market Intelligence | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Cost Optimization | records | 1 | 0 | Native records/view |
| Contracts | records | 1 | 0 | Native records/view |
| Pricing Rules | records | 1 | 0 | Native records/view |
| Audit Trail | records | 1 | 0 | Native records/view |
| Hub | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Deliveries | records | 1 | 0 | Native records/view |
| Warehouses | records | 2 | 0 | Native records/view |
| Zones | records | 1 | 0 | Native records/view |
| Packages | records | 1 | 0 | Native records/view |
| SLAs | records | 1 | 0 | Native records/view |
| Performance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SLA Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof of Delivery | records | 1 | 0 | Native records/view |
| Returns | records | 1 | 0 | Native records/view |
| Public Tracking | records | 1 | 0 | Native records/view |
| Delivery Time Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecasting | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Improvement Suggestions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fleet Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver-Route Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Churn Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dynamic Pricing Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vehicle Maintenance Alert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Porch piracy risk map | records | 1 | 0 | Native records/view |
| Container Yard | records | 2 | 0 | Native records/view |
| Berth Scheduling | records | 2 | 0 | Native records/view |
| Vessel Routes | records | 2 | 0 | Native records/view |
| Customs Pre-clearance | records | 2 | 0 | Native records/view |
| Cargo Tracking | records | 2 | 0 | Native records/view |
| Port Traffic | records | 2 | 0 | Native records/view |
| Weather Impact | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Crew Management | records | 2 | 0 | Native records/view |
| Port Equipment | records | 2 | 0 | Native records/view |
| Warehouse Mgmt | records | 2 | 0 | Native records/view |
| Voyage Planning | records | 2 | 0 | Native records/view |
| Shipping Lines | records | 2 | 0 | Native records/view |
| Port Tariffs | records | 2 | 0 | Native records/view |
| Tide Schedules | records | 2 | 0 | Native records/view |
| Port Notices | records | 2 | 0 | Native records/view |
| Reefer Plugs | records | 1 | 0 | Native records/view |
| Liability Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental Compliance Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Container Yard Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vessel Route Optimization | records | 1 | 0 | Native records/view |
| Fuel Consumption Modeling | records | 1 | 0 | Native records/view |
| Port Traffic Management | records | 1 | 0 | Native records/view |
| Weather Impact Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Port Equipment Management | records | 1 | 0 | Native records/view |
| Incident Reports | records | 1 | 0 | Native records/view |
| Dock Inspections | records | 1 | 0 | Native records/view |
| Warehouse Management | records | 1 | 0 | Native records/view |
| Shipping Lines Directory | records | 1 | 0 | Native records/view |
| Shipping Documents | records | 1 | 0 | Native records/view |
| AI Chat Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Report Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scenario Simulator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reshoring decision | records | 1 | 0 | Native records/view |
| Scenario bundles | records | 1 | 0 | Native records/view |
| Geographic risk | records | 1 | 0 | Native records/view |
| Labor cost forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Site risk score | records | 1 | 0 | Native records/view |
| Tariff impact forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain resilience score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Port drayage constraint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| labor arbitrage modeling comparing wage productivity training costs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| supply chain resilience scoring quantifying single sourcing and geopolitical | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| regulatory complexity assessment flagging esg fta reporting burden | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| build vs partner optimization comparing capex opex vs continued outsourcing | records | 1 | 0 | Native records/view |
| monte carlo scenario planning for tariff labor currency | records | 1 | 0 | Native records/view |
| nearshoring specific recommendation engine for mexico canada | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai endpoints under enumerated should expose labor cost prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| scenario comparison endpoint | records | 1 | 0 | Native records/view |
| conversational reshoring advisor chat | records | 1 | 0 | Native records/view |
| integrations with public data apis bls un | integration | 1 | 0 | Provider request records only |
| scenario modeling comparison ui route | records | 1 | 0 | Native records/view |
| feasibility scoring decision tree | records | 1 | 0 | Native records/view |
| project management for reshoring initiatives | records | 1 | 0 | Native records/view |
| webhooks or external notifications | integration | 2 | 0 | Provider request records only |
| multi tenant client workspace separation | records | 1 | 0 | Native records/view |
| predictive quality issues flagging suppliers routes with quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| network optimization recommending facility sourcing locations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| last mile delivery optimization with route and consolidation recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| blockchain traceability for high value regulated shipments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| supplier collaboration portal with exception escalation | records | 1 | 0 | Native records/view |
| iot sensor stream ingestion for cold chain compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai driven network optimization facility sourcing point placement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive quality scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai driven freight cost optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| iot sensor ingestion temperature humidity for cold | records | 1 | 0 | Native records/view |
| customer portal for shipment visibility | records | 1 | 0 | Native records/view |
| 3pl integration | integration | 1 | 0 | Provider request records only |
| freight cost analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi tenant operator separation | records | 1 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Disruptions | records | 1 | 0 | Native records/view |
| Inventory | records | 1 | 0 | Native records/view |
| Orders | records | 1 | 0 | Native records/view |
| Quality | records | 1 | 0 | Native records/view |
| Fleet agents | records | 1 | 0 | Native records/view |
| Shipment map | records | 1 | 0 | Native records/view |
| Weekly plan | records | 1 | 0 | Native records/view |
| Usage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Optimize network | records | 1 | 0 | Native records/view |
| Optimize last mile | records | 1 | 0 | Native records/view |
| Detention demurrage exposure | records | 1 | 0 | Native records/view |
| Room Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Home Staging | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Furniture Placer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Home Inspector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multimodal redesign | integration | 1 | 0 | Provider request records only |
| Ar furniture pricing | records | 1 | 0 | Native records/view |
| Design canvas session | integration | 1 | 0 | Provider request records only |
| Contractor skill match | records | 1 | 0 | Native records/view |
| Design trend analysis | integration | 1 | 0 | Provider request records only |
| Smart home integration | integration | 1 | 0 | Provider request records only |
| Floor plans | records | 1 | 0 | Native records/view |
| Rooms | records | 1 | 0 | Native records/view |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full analyses | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Room detection | records | 1 | 0 | Native records/view |
| Optimize layout | records | 1 | 0 | Native records/view |
| Furniture placement | records | 1 | 0 | Native records/view |
| Maintenance prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy audit | records | 1 | 0 | Native records/view |
| Home inspection | records | 1 | 0 | Native records/view |
| Suggestions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Estimates | records | 1 | 0 | Native records/view |
| Dimensions | records | 1 | 0 | Native records/view |
| Contractors | records | 1 | 0 | Native records/view |
| Designs | integration | 1 | 0 | Provider request records only |
| Design | integration | 1 | 0 | Provider request records only |
| Styles | records | 1 | 0 | Native records/view |
| Furniture | records | 1 | 0 | Native records/view |
| Palettes | records | 1 | 0 | Native records/view |
| Ar | records | 1 | 0 | Native records/view |
| Shopping | records | 1 | 0 | Native records/view |
| Inspirations | records | 1 | 0 | Native records/view |
| Materials | records | 1 | 0 | Native records/view |
| Subscription | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Material contractor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bin replenishment queue | records | 1 | 0 | Native records/view |
| Multi modal vision analyze floorplan photos measurements sim | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ar preview with live furniture price availability integratio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real time collaborative design canvas with multi user edits | integration | 1 | 0 | Provider request records only |
| Contractor marketplace with ai skill matching and reputation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Historical design trend analysis across client portfolio | integration | 1 | 0 | Provider request records only |
| Integration with smart home systems lighting placement hvac | integration | 1 | 0 | Provider request records only |
| Predictive material wear and lifespan modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contractor matching ai based on skill geography and project | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client preference learning from past design choices | integration | 1 | 0 | Provider request records only |
| Generative variant exploration alternate layouts in seconds | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoicepayment tracking and milestone billing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client communication portal messaging thread | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project timeline gantt tracking with dependencies | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bulk import from photos folder ingest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendorsupplier order tracking integrated to shopping lists | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost estimate | records | 1 | 0 | Native records/view |
| Design tools | integration | 1 | 0 | Provider request records only |
| Style presets | records | 1 | 0 | Native records/view |
| Furniture catalog | records | 1 | 0 | Native records/view |
| Color palettes | records | 1 | 0 | Native records/view |
| Ar viewer | records | 1 | 0 | Native records/view |
| Shopping lists | records | 1 | 0 | Native records/view |
| Shipping work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 565 feature pages were visited in the browser; 563 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 361 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

361 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
