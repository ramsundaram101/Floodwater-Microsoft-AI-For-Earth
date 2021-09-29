# Floodwater-Microsoft-AI-For-Earth
Microsoft AI For Earth Floodwater Mapping Competition - https://www.drivendata.org/competitions/81/detect-flood-water/page/385/


Overview

As global warming exacerbates rising sea levels and extreme weather events, flooding has become the most frequent, costly, and devastating natural disaster in the world. Defined by the U.S. Geological Survey as the temporary submergence of land that is usually dry by an overflow of water, floods are typically caused by runoff from excessive rainfall over a short period of time, a prolonged rainstorm, or melting snow. According to the World Health Organization, between 1998 and 2007, floods affected more than 2 billion people worldwide.

It is critical that governments and humanitarian organizations be able to accurately measure flood extent in near real-time to strengthen early warning systems, assess risk, target relief, and save lives. Conventionally, flooding has been measured by monitoring systems that rely on a combination of ground equipment and complex hydrological simulations. Rain and stream gauging stations, however, only measure water height, and are limited by geographic placement and cost of maintenance.

Over the past several years, high resolution satellite imagery has strengthened monitoring systems by providing data in otherwise inaccessible areas at frequent time intervals. Specifically, sensors operating in the microwave portion of the electromagnetic spectrum provide critical information on the presence of floodwater in a scene regardless of cloud coverage.


Sentinel-1

The Sentinel-1 mission comprises two satellites performing C-band (4 to 8 GHz) synthetic-aperture radar (SAR) imaging, which provides an all-weather, day-and-night supply of images of Earth’s surface. As compared with optical sensors that detect energy reflected in the visible and infrared spectral bands, SAR systems operate in the microwave band, where long waves can penetrate through clouds, vegetation, fog, rain showers, and snow.

Sentinel-1 imagery is among the environmental monitoring data made available through Microsoft's new Planetary Computer. The Planetary Computer combines a multi-petabyte catalog of analysis-ready environmental data with intuitive APIs and a flexible development environment to support scientists, developers, and policy makers applying artificial intelligence to environmental challenges. The Planetary Computer uses the SpatioTemporal Asset Catalog (STAC) standard for organizing geospatial assets and metadata, making it easy to search for data that match spatial, temporal, or other criteria.


Task

The goal of this challenge is to build machine learning algorithms that are able to map floodwater using Sentinel-1 global SAR imagery. Microsoft AI for Earth has teamed up with DrivenData and Cloud to Street to investigate the applicability of machine learning models for detecting flood coverage in near real-time. Models that leverage SAR imaging will significantly improve flood risk assessment, relief targeting, and ultimately, disaster readiness and response.
