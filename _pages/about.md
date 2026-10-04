---
layout: page
permalink: /about/
title: About SatMapKit
description: Tools and research context for satellite altimetry workflows.
eyebrow: About
---

SatMapKit brings together tools for satellite altimetry research. The projects support experiments with simulated satellite sampling and workflows for querying and mapping ocean observations.

## The projects

[AlongTrackSimulator](https://satmapkit.github.io/AlongTrackSimulator/) simulates satellite ground tracks and samples numerical ocean models using the patterns of real altimetry missions. It is a MATLAB package available through [OceanKit](https://github.com/JeffreyEarly/OceanKit).

[OceanDB](https://github.com/satmapkit/OceanDB) organizes along-track altimetry observations and eddy datasets for spatial and temporal queries using Python and PostgreSQL/PostGIS.

[MapInterp](https://github.com/satmapkit/MapInterp) uses observations from OceanDB to interpolate sea-level data onto query points and grids with interchangeable interpolation methods.

## Research context and credits

AlongTrackSimulator is maintained by Jeffrey J. Early. Its [acknowledgements](https://github.com/satmapkit/AlongTrackSimulator/blob/main/Documentation/WebsiteDocumentation/acknowledgements.md) document NASA support and provide citation information for that project.

## Explore and contribute

Visit the [toolkit]({{ '/tools/' | relative_url }}) to find a project, or browse the [SatMapKit organization on GitHub](https://github.com/satmapkit). Each project's repository is the place to find its source code and contribution discussions.
