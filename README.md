# CO2 Pipeline Social Analytics

This repository contains an **ArcGIS Pro** project used for mapping the social and economic impacts of a proposed carbon dioxide pipeline.
It provides project files, packaged maps and a file geodatabase that can be opened directly within ArcGIS Pro.

## Repository contents

- **`co2_pipeline_social_analytics.aprx`** – Main ArcGIS Pro project. Opening this file loads the maps and connects to the geodatabase and toolboxes in this folder.
- **`co2_pipeline_social_analytics.gdb/`** – File geodatabase storing spatial layers and analysis results referenced by the project.
- **`Economic.pitemx`** and **`Midwest_landuse.pitemx`** – Item packages that reference hosted feature and tile layers on ArcGIS Online. Import these into ArcGIS Pro if they are not already in the project.
- **`MyProject3.atbx`** – Geoprocessing toolbox with custom tools used in the analysis.

## Requirements

- [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview) 3.x or later.
- An ArcGIS Online account may be needed to access the hosted layers referenced by the `.pitemx` files.

## Usage

1. Clone or download this repository.
2. Open `co2_pipeline_social_analytics.aprx` in ArcGIS Pro.
3. If the packaged items are not automatically loaded, import `Economic.pitemx` and `Midwest_landuse.pitemx` using **Insert → Import Map**.
4. Add the toolbox `MyProject3.atbx` if you need the custom geoprocessing tools.
5. The included geodatabase will be recognized automatically when the project is opened.

These resources demonstrate the workflows used in studying the pipeline's potential impact. Feel free to adapt them for your own analysis.
