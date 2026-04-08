## GIS Suitability Analysis for Student Housing

This project uses ArcGIS Pro to identify optimal locations for student housing development in Harrisonburg, Virginia. 
A GIS-based suitability model was created by integrating zoning, slope (DEM), property value, and distance-to-campus data through raster analysis and map algebra.

The final output highlights feasible and cost-effective development areas
showing that the most suitable locations are concentrated within close proximity to James Madison University.

### Methods
- Raster reclassification (zoning, slope, property value)
- DEM-derived slope analysis
- Euclidean distance buffers for campus proximity
- Raster Calculator (map algebra) to combine criteria

### Data Sources
- City of Harrisonburg GIS (zoning)
- USGS DEM data (elevation/slope)
- PolicyMap (property values)
- ArcGIS Online (JMU location)

### Tools
- ArcGIS Pro
- Spatial Analyst Toolbox

### Output
- Final suitability map identifying optimal student housing locations
