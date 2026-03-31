# Industrial Site Selection Using GIS Analysis

## Project Overview
This project identifies suitable locations for an industrial facility using **ArcGIS Pro** and **ModelBuilder**. The analysis incorporates environmental constraints, transportation infrastructure, and land use requirements to find optimal sites.

## Business Problem
An industrial company needs to select a new facility location that balances:
- **Environmental protection** (≥200m from water bodies)
- **Transportation access** (≤500m from roads/railroads)
- **Land requirements** (agricultural land ≥50 hectares)

## Tools & Technologies
- **ArcGIS Pro** (Geoprocessing, ModelBuilder)
- **Spatial Analysis** (Buffer, Select by Attribute, Select by Location)
- **Python** (Automation script exported from ModelBuilder)

## Methodology
![ModelBuilder Workflow](model_screenshot.png)

### Criteria Applied:
1. **Environmental Buffer**: 200m from rivers
2. **Transportation Buffer**: 500m from roads
3. **Land Use Filter**: Agricultural parcels only
4. **Size Filter**: ≥50 hectares (500,000 sq meters)

## Results
| Site_ID | Area (sq m) | Area (hectares) |
|---------|-------------|-----------------|
| 1       | 525,000     | 52.5            |
| 2       | 510,000     | 51.0            |
| 3       | 548,000     | 54.8            |

![Final Map](Final_Map.pdf)

## How to Reproduce
1. Download `SiteSelection.gdb` and open in ArcGIS Pro
2. Run the model `industrial_site_model.py` or open ModelBuilder
3. Export results and map layout

## Skills Demonstrated
- ✅ Spatial analysis and geoprocessing
- ✅ ModelBuilder automation
- ✅ Cartographic design and map production
- ✅ Professional documentation

## Author
[Kalusha Aguti]  
[kalushaaguti@gmail.com]  
[linkedin.com/in/kalusha-aguti-654006189]
