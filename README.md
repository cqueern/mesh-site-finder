# Mesh Site Finder

**Mesh Site Finder** is a lightweight web application for identifying, mapping, and evaluating potential locations for wireless mesh nodes—especially fixed, solar-powered, rooftop, tower, mast, or infrastructure-mounted deployments.

The goal is to help communities build more resilient, better-placed wireless mesh networks by making it easier to identify elevated structures and other locations that may be well suited for long-range radio coverage.

---

## What This Is

Mesh Site Finder is designed to help answer questions such as:

- Where should I put a fixed mesh node to improve coverage?
- Which tall structures could potentially host a solar-powered relay?
- What elevated mounting locations exist near a particular area?
- How can a community coordinate infrastructure placement instead of guessing?

The application focuses on **site discovery and planning**, rather than device configuration or live network telemetry.

---

## Core Features

### Interactive Map

- Search by US ZIP code
- Select a search radius
- Pan and zoom through candidate locations
- View candidate structures directly on a map

### Structure-Oriented Discovery

- Searches for tall buildings, towers, and masts
- Uses available OpenStreetMap structure and height information
- Highlights locations that may be suitable for rooftop, mast-mounted, or solar-powered nodes

### Infrastructure Context

- Identifies selected nearby infrastructure
- Provides additional geographic context when evaluating candidate sites
- Helps support community and resilience-oriented network planning

### Candidate Scoring

Candidate sites are evaluated using factors including:

- Estimated structure height
- Nearby infrastructure
- Proximity to relevant sites

Scores are intended as planning aids rather than engineering guarantees.

### Data Export

Search results can be exported as:

- CSV
- GeoJSON

This allows candidate locations to be analyzed in spreadsheets, GIS applications, or other planning tools.

### Lightweight Architecture

- Runs entirely in the browser
- Uses OpenStreetMap and public data sources
- Requires no application server
- Suitable for static hosting such as GitHub Pages

---

## What This Is Not

Mesh Site Finder is:

- Not a live wireless mesh network monitor
- Not a replacement for radio firmware or network management applications
- Not a radio propagation simulator
- Not a guarantee that a candidate location is deployable
- Not authoritative infrastructure or surveying data
- Not a substitute for obtaining permission from property owners

---

## Height and Elevation Disclaimer

Structure height and elevation data may be incomplete, estimated, or unavailable.

Where explicit structure height data is unavailable, the application may estimate height from other available information such as building levels or structure type.

Elevation values are not normalized to sea level.

The tool does not account for mean sea level (MSL), geoid models, tidal reference systems, detailed terrain obstruction, vegetation, building attenuation, Fresnel zones, antenna characteristics, or other factors necessary for professional RF propagation analysis.

Treat all height, elevation, distance, and site-ranking information as approximate.

Always validate elevation, line-of-sight, RF propagation, structural suitability, ownership, access, regulatory requirements, and mounting assumptions before deploying equipment.

---

## Use Cases

- Community wireless mesh networks
- Emergency communications planning
- Resilience and preparedness projects
- Amateur radio experimentation
- LoRa network planning
- Maker and hacker groups
- Educational demonstrations
- Fixed and solar-powered relay planning
- Preliminary rooftop and tower site identification

---

## Data Sources

Mesh Site Finder uses publicly available geographic information, including OpenStreetMap data.

The quality and completeness of results depend on the data available for the area being searched.

---

## Safety and Permission

Always obtain permission before installing equipment on property you do not own.

Follow applicable radio regulations, electrical and structural requirements, building codes, antenna-placement restrictions, and safe installation practices.

Mesh Site Finder identifies potential locations only. It does not establish ownership, availability, permission, structural suitability, or legal authorization to install equipment.
