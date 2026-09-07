# Feature status — Agriculture, fisheries & food production

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 338 pages |
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
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 7 | 0 | Native records/view |
| Activity & audit trail | audit | 10 | 0 | Native records/view |
| Provider connections | integration | 5 | 0 | Provider request records only |
| Supplier program library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farm account registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product eligibility mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase transaction ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Acre application evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Volume tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product bundle validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Early order incentive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loyalty status control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate claim preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farm supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quota Account | records | 1 | 0 | Native records/view |
| Fishing Vessel | records | 1 | 0 | Native records/view |
| Quota Allocation | records | 1 | 0 | Native records/view |
| Quota Transfer | records | 1 | 0 | Native records/view |
| Fishing Trip | records | 1 | 0 | Native records/view |
| Landing Record | records | 1 | 0 | Native records/view |
| Landing Correction | records | 1 | 0 | Native records/view |
| Quota Lease | records | 1 | 0 | Native records/view |
| Fishery Report | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Landing ticket extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Species and unit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quota variance explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer document completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Landing correction brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fishery report narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fields | records | 2 | 0 | Native records/view |
| Pest Detections | records | 1 | 0 | Native records/view |
| Treatment Plans | records | 3 | 0 | Native records/view |
| Health Reports | records | 1 | 0 | Native records/view |
| Sensor Devices | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Weather | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Field Operations | records | 1 | 0 | Native records/view |
| Spray window | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Residue risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Soil health | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Disease early warning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beneficial insects | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Export | records | 2 | 0 | Native records/view |
| Search | records | 1 | 0 | Native records/view |
| Sample data | records | 1 | 0 | Native records/view |
| Pest photo classifier | records | 1 | 0 | Native records/view |
| Sensor anomaly | records | 1 | 0 | Native records/view |
| Crop rotation | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Treatment efficacy | records | 1 | 0 | Native records/view |
| Residue audit | records | 1 | 0 | Native records/view |
| Biocontrol market | records | 1 | 0 | Native records/view |
| Coop heatmaps | records | 1 | 0 | Native records/view |
| Drone vision | records | 1 | 0 | Native records/view |
| Federated weather | records | 1 | 0 | Native records/view |
| Image upload | records | 1 | 0 | Native records/view |
| Multi tenant farms | records | 1 | 0 | Native records/view |
| Offline sync | records | 1 | 0 | Native records/view |
| Weather providers | records | 1 | 0 | Native records/view |
| Stumpage agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tract cruise inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Species grade mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest load ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scale ticket validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mill receipt matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weight conversion factors | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Board-foot calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Index price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hauling deduction audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Road cost deduction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Logger mill dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cash reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tract species analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Onboarding | records | 1 | 0 | Native records/view |
| Crop diseases | records | 1 | 0 | Native records/view |
| Irrigation | records | 1 | 0 | Native records/view |
| Harvest | records | 1 | 0 | Native records/view |
| Pests | records | 1 | 0 | Native records/view |
| Soil | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Feedback | records | 1 | 0 | Native records/view |
| Yield prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Pest forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subsidies | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farm chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon footprint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weekly report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Results | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Weather risk alert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Soil amendment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Disease id text | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market price prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability score | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Irrigation optimize text | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Irrigation realtime | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Iot sensor summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farms | records | 1 | 0 | Native records/view |
| Net Pens | records | 1 | 0 | Native records/view |
| Fish Groups | records | 1 | 0 | Native records/view |
| Feed Inventory | records | 2 | 0 | Native records/view |
| Mortality Logs | records | 1 | 0 | Native records/view |
| Water Quality | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Biomass Estimates | records | 1 | 0 | Native records/view |
| Sea Lice Counts | records | 1 | 0 | Native records/view |
| Vessels | records | 1 | 0 | Native records/view |
| Divers | records | 1 | 0 | Native records/view |
| Harvests | records | 2 | 0 | Native records/view |
| Certifications | records | 1 | 0 | Native records/view |
| Predator Incidents | records | 1 | 0 | Native records/view |
| Environmental Impacts | records | 1 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| AI - Biomass Vision | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Sea Lice Classify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Feed Conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Mortality Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Treatment Recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Executive Brief | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI - Harvest Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Water Quality Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Predator Deterrent | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Environmental Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Vessel Shift Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Diver Safety Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Customer Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Cert Readiness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Vendor Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI - Market Price Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stocking density risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fish health diagnostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Biomass forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest timing | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Mortality predict | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Pen camera analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Escape detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feeding schedules | records | 1 | 0 | Native records/view |
| Water quality ingest | records | 1 | 0 | Native records/view |
| Regulatory reports | records | 1 | 0 | Native records/view |
| Webhooks | integration | 3 | 0 | Provider request records only |
| Apiaries | records | 1 | 0 | Native records/view |
| Hives | records | 1 | 0 | Native records/view |
| Queens | records | 1 | 0 | Native records/view |
| Inspections | records | 1 | 0 | Native records/view |
| Honey Harvests | records | 1 | 0 | Native records/view |
| Supplies | records | 1 | 0 | Native records/view |
| Equipment | records | 3 | 0 | Native records/view |
| Beekeepers | records | 1 | 0 | Native records/view |
| Pollination Contracts | records | 1 | 0 | Native records/view |
| Plant Sources | records | 1 | 0 | Native records/view |
| Weather Briefs | records | 1 | 0 | Native records/view |
| Disease Outbreaks | records | 1 | 0 | Native records/view |
| Swarms | records | 1 | 0 | Native records/view |
| Varroa Counts | records | 1 | 0 | Native records/view |
| Hive Sounds | records | 1 | 0 | Native records/view |
| AI · Queen Status From Sound | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Varroa Treatment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Swarm Risk Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Pollination Route Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Hive Strength Trend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Harvest Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Treatment Efficacy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Customer Quote | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weather Impact Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Disease Outbreak Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Supply Resupply Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Beekeeper Schedule | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Plant Source Map | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Equipment Prognostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quote Compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hive acoustic anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Varroa risk score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Queen health assess | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Beekeeper mentor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foraging optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nectar flow calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treatment labels | records | 1 | 0 | Native records/view |
| Pesticide setbacks | records | 1 | 0 | Native records/view |
| Market prices | records | 3 | 0 | Native records/view |
| Biosecurity scores | records | 1 | 0 | Native records/view |
| Contract revenue models | records | 1 | 0 | Native records/view |
| Genetic resilience | records | 1 | 0 | Native records/view |
| Queen lineage | records | 1 | 0 | Native records/view |
| Grow rooms | records | 1 | 0 | Native records/view |
| Plants | records | 1 | 0 | Native records/view |
| Compliance | records | 2 | 0 | Native records/view |
| Yield predictions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lab tests | records | 1 | 0 | Native records/view |
| Inventory | records | 1 | 0 | Native records/view |
| Strains | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waste records | records | 1 | 0 | Native records/view |
| Environmental alerts | records | 1 | 0 | Native records/view |
| Regulatory tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| License renewal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Microbial analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Harvest readiness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pest detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Energy optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seed supplier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seasonal Risk Calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cross-Farm Benchmarking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fertilizer Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weather Trigger Alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Treatment Efficacy Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Marketplace Match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Yield | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Optimize Harvest Timing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| IPM Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest disease window | records | 1 | 0 | Native records/view |
| Multi modal crop health assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farmer decision support | records | 1 | 0 | Native records/view |
| Supply chain optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Integrated pest management ipm automation | records | 1 | 0 | Native records/view |
| Marketplace expert consultations lack ai driven matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Farm management lacks ai yield forecasting endpoint | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community reports lacks ai moderation clustering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No mobile field capture app surfaces beyond rest api | records | 1 | 0 | Native records/view |
| No webhooks for sensor weather pushes | integration | 1 | 0 | Provider request records only |
| No sms or push notifications | records | 1 | 0 | Native records/view |
| No payment marketplace transaction handling | records | 1 | 0 | Native records/view |
| No calendar integration only internal crop calendar | integration | 1 | 0 | Provider request records only |
| Fish Stock Modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feed Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disease Detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Vision Diagnosis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor Monitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Species | records | 1 | 0 | Native records/view |
| Ponds & Tanks | records | 1 | 0 | Native records/view |
| Employees | records | 1 | 0 | Native records/view |
| Financial | records | 1 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Stocking permit planner | records | 1 | 0 | Native records/view |
| Agentic farm | records | 1 | 0 | Native records/view |
| Disease Outbreak Check | records | 1 | 0 | Native records/view |
| Timber Market Alert | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| GIS Harvest Block Planner | records | 1 | 0 | Native records/view |
| Wildfire Weather Scan | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Safety Incident Analyser | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reforestation Plan | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Review | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tree Inventory | records | 1 | 0 | Native records/view |
| Harvest Plans | records | 1 | 0 | Native records/view |
| Wildfire Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon Credits | records | 1 | 0 | Native records/view |
| Forest Plots | records | 1 | 0 | Native records/view |
| Workers | records | 1 | 0 | Native records/view |
| Disease Reports | records | 1 | 0 | Native records/view |
| Timber Sales | records | 1 | 0 | Native records/view |
| agentic forest planning multi agent syst | records | 1 | 0 | Native records/view |
| drone fused canopy cv extend canopy | records | 1 | 0 | Native records/view |
| buyer demand matching predictive marketp | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| real time mqtt broker integration for | integration | 1 | 0 | Provider request records only |
| regulatory rag assistant over usfsstate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| carbon market arbitrage compares verra v | records | 1 | 0 | Native records/view |
| dedicated wildfire spread simulation | records | 1 | 0 | Native records/view |
| vendorsupplier matching ai only telem | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| labor scheduling ai for field | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| soprag over forestry regulations defe | records | 1 | 0 | Native records/view |
| modular tree inventory crud only | records | 1 | 0 | Native records/view |
| teamshift scheduling for field operat | records | 1 | 0 | Native records/view |
| equipment fleet crud beyond predictiv | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| cost tracking pl module | records | 1 | 0 | Native records/view |
| real iot mqtt broker telemetry | records | 1 | 0 | Native records/view |
| monolithic structure makes route discove | records | 1 | 0 | Native records/view |
| Species identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Harvest optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wildfire risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon estimation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disease analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disease outbreak | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gis harvest blocks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety incident analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment maintenance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Safety incidents | records | 1 | 0 | Native records/view |
| Disease Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Breeding Advisor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Health Anomaly Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Nutrition Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Economic Forecaster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Animal Registry | records | 1 | 0 | Native records/view |
| Health Records | records | 1 | 0 | Native records/view |
| Vaccination Tracking | records | 1 | 0 | Native records/view |
| Feed Management | records | 1 | 0 | Native records/view |
| Weight Tracking | records | 1 | 0 | Native records/view |
| Breeding Records | records | 1 | 0 | Native records/view |
| Veterinary Visits | records | 1 | 0 | Native records/view |
| Medication Tracking | records | 1 | 0 | Native records/view |
| Herd Management | records | 1 | 0 | Native records/view |
| Alert System | records | 1 | 0 | Native records/view |
| Milk Production | records | 1 | 0 | Native records/view |
| Mortality Records | records | 1 | 0 | Native records/view |
| Financial Reports | records | 1 | 0 | Native records/view |
| Parasite grazing rotation | records | 1 | 0 | Native records/view |
| Weather Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Crop Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pest & Disease Alerts | records | 1 | 0 | Native records/view |
| Irrigation Plans | records | 1 | 0 | Native records/view |
| Harvest Planning | records | 1 | 0 | Native records/view |
| Market Trends | records | 1 | 0 | Native records/view |
| Financial Planning | records | 1 | 0 | Native records/view |
| Satellite Imagery | records | 1 | 0 | Native records/view |
| Equipment Management | records | 1 | 0 | Native records/view |
| Labor Planning | records | 1 | 0 | Native records/view |
| Sustainability Metrics | records | 1 | 0 | Native records/view |
| Multimodal yield | records | 1 | 0 | Native records/view |
| Drone pest detection | records | 1 | 0 | Native records/view |
| Commodity forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Microclimate | records | 1 | 0 | Native records/view |
| Water optimize | records | 1 | 0 | Native records/view |
| Equipment failure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Extension services | records | 1 | 0 | Native records/view |
| Market trend forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pest outbreak prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Irrigation optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 338 feature pages were visited in the browser; 336 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 175 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

175 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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
