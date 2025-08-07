**Guidance for Mapping Suitability and Susceptibility Layers**

**2. Selection or Filtering**
Intersected suitability and susceptibility layers contain classification information (e.g., "Very Suitable", "Highly Susceptible") linked to administrative boundaries — sector, cell, and village.
Users should be able to filter or select by these administrative levels to view corresponding suitability distributions.
For example, selecting a sector should display all intersected polygons within it and compute the total area (in hectares) for each suitability class.
Note: Selection can be performed either on the intersected layer itself or on the administrative boundary layers (sector, cell, village) — provided we can retrieve all polygons within the selected unit and aggregate their area using the area_ha field.

**3. Visualizations**
**3.1 Susceptibility Layer**
Susceptibility classes and their color codes:

**Susceptibility Class	Color Code**
Extremely Susceptible	#A80000
Highly Susceptible	#FF5500
Moderate Susceptible	#F5CA7A
Slightly Susceptible	#E1E1E1

**Overlay layers:**
Restricted Areas
District Boundary
Sectors (always visible)
Cells and Villages (visible upon selection)

**3.2 Suitability Layer**
Crop suitability classes and their color codes:

**Suitability Class	Color Code**
Very Suitable	#38A800
Suitable	#98E600
Moderate Suitable	#E9FFBE
Less Suitable	#FFEBAF
Not Suitable	#FF5500

**Overlay layers:**
Restricted Areas
District Boundary
Sectors (always visible)
Cells and Villages (visible upon selection)

**Visualization Settings**
Polygon Boundaries: Set polygon boundaries of the suitability_class and susceptibility_class layers to zero width to improve visual clarity.

