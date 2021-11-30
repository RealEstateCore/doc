# RealEstateCore v3.3

**Modules:**
* [Metadata](metadata.html) -- Various annotation properties used to document the entire ontology suite.
* [Units](units.html) -- Datatypes, measurement units, and quanity kinds used in RealEstateCore (a subset of [QUDT](http://qudt.org))
* [Core](core.html) -- Collects the top-level classes and properties that span over or are reused within multiple REC modules. Imports the Metadata and Units modules, and is imported by all other specific child modules.
* [Addessing](addressing.html) -- The addressing module; message semantics for requesting and enacting actuation on building systems.
* [Actuation](actuation.html) -- The actuation model; message semantics for requesting and enacting actuation on building systems.
* [Agents](agents.html) -- Basic types of agents (people, organizations, companies, departments).
* [Analytics](analytics.html) --  A vocabulary for describing prognoses and aggregates, and the processes used to generate these.
* [Asset](asset.html) --  An extensive categorisation of assets within buildings, e.g., equipment, systems, furniture, architectural/installed assets, etc.
* [Building](building.html) -- Different types of building components and rooms.
* [Business](business.html) -- Covers leases and lease contracts, business roles, etc. 
* [Data schemas](dataschemas.html) -- Primitive and complex (object/array) data schemas for sensors, actuators, services, etc.
* [Device](device.html) -- Device types (sensors and actuators), device configuration, device actuation, etc.
* [LFR](lfr.html) -- Optional module covering the data model used by the Swedish National Land Survey, in its database Swedish Real Property Register (Lantmäteriets Fastighetsregister). Not included in the Full ontology below.

**Composed Ontology:**
* [REC Full](full.html) -- Imports all REC modules, providing the fullest possible expressivity.
