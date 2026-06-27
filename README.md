# vector-osmnx-tree-analysis

A Python‑based vector workflow analyzing street tree density across Cambridge, MA zoning districts using GeoPandas, OSMnx, and OpenStreetMap road networks.

## Tech Stack
- Python
- GeoPandas
- OSMnx
- Matplotlib

## Workflow
- Load zoning polygons and group them into broad categories.
- Load street tree point data from Cambridge GIS.
- Use OSMnx to extract road networks and compute road length per zone.
- Calculate trees-per-meter metrics for each zone category.
- Identify the most common tree species per zone.
- Visualize results using Python-only geospatial plotting.

## Data Sources
- Cambridge Zoning Categories:https://www.cambridgema.gov/-/media/Files/CDD/Maps/Zoning/cddmap_zoning_base_11x17_20240221.pdf
- Cambridge GIS Zoning Districts: https://www.cambridgema.gov/GIS/gisdatadictionary/CDD/CDD_ZoningDistricts
- Cambridge GIS Street Trees: https://www.cambridgema.gov/GIS/gisdatadictionary/Environmental/ENVIRONMENTAL_StreetTrees
- Road Network: OpenStreetMap (via OSMnx)

 I took inspiration for this project from the [Python Foundation series](https://www.youtube.com/playlist?list=PLppGmFLhQ1HJspXSA0asH9kw1OhlLrxHT) by Spatial Thoughts.

![image](https://github.com/user-attachments/assets/e8fc942b-1d7f-4563-9bf5-bfe109570609)
