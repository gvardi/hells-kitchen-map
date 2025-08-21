# Hell's Kitchen Building Map Package

This package contains an interactive map of Hell's Kitchen buildings with financing data and conversion analysis.

## Files Included:

- **hells_kitchen_map.html** - The main interactive map file with enhanced features
- **hells_kitchen_financing_report_latest.csv** - Latest building data with conversion analysis (306 buildings)
- **hells_kitchen_crime_heatmap.html** - Crime incident heatmap visualization
- **input/** - Shapefile data for district boundaries
  - HellsKitchen.* - Hell's Kitchen boundary
  - CouncilDistrict.* - Council District boundary  
  - communityBoard.* - Community Board 4 boundary

## How to Use:

1. **Open the map**: Double-click `hells_kitchen_map.html` to open it in your web browser
2. **Navigate**: Use mouse to pan and zoom around the map
3. **View buildings**: Click on building markers to see detailed information
4. **Control panel**: Use the statistics panel on the left side for:
   - Viewing building statistics and district breakdowns
   - Toggling boundary fills on/off
   - Folding/unfolding the panel to save space
   - **Downloading complete data** as CSV file
5. **Responsive design**: The map adapts to different screen sizes automatically

## Map Features:

- **Building Markers**: 
  - Red building icons = Buildings without financing documents
  - Blue dollar signs = Buildings with mortgage financing
  - Purple dollar signs = Buildings with deed financing
  - Green dollar signs = Buildings with other financing types
- **Building Information**: Each marker shows detailed information including:
  - Building area and rentable square footage
  - Number of floors and average rentable sqft per floor
  - Year built and last known alteration
  - Financing details and financial metrics
  - **NEW: Conversion analysis data** (building depth, frontage, corner lot status)
  - **NEW: Vacancy data** (vacancy rate, hotel status, conversion suitability)
- **District Boundaries**: 
  - Red = Hell's Kitchen
  - Orange = Council District
  - Purple = Community Board 4
- **Integrated Controls**: 
  - Statistics panel with fold/unfold functionality
  - Boundary fill toggle
  - **NEW: Data export functionality** - Download complete dataset as CSV
  - Responsive design for mobile and desktop
- **Background Options**: Switch between different map backgrounds
- **ZOLA Links**: Click on building markers to view property details with direct links to NYC ZOLA records

## NEW: Enhanced Data Features

### **Conversion Analysis Data:**
- **Building Depth**: Calculated depth in feet
- **Building Frontage**: Calculated frontage in feet  
- **Corner Lot Status**: Whether the building is on a corner lot
- **Building Metrics**: Number of floors and average rentable sqft per floor

### **Vacancy & Conversion Data:**
- **Vacancy Rate**: Current vacancy percentage for each building
- **Hotel Status**: Whether the building is currently a hotel
- **Not for Conversion**: Reasons why buildings are not suitable for conversion (e.g., "Mini Storage", "Appartments", "Chelsea Piers", "Google")

### **Data Export:**
- **Download Complete Data**: Click the "📊 Download Complete Data" button in the left panel
- **Comprehensive CSV**: Includes all financial and conversion analysis data
- **Filtered Data**: Only includes buildings meeting criteria (CD4/CD3, ≤1990, ≥100k sqft)

### **Updated Filtering:**
- **Geographic**: Community District 4 OR Council District 3
- **Size**: Buildings ≥ 100,000 square feet
- **Age**: Buildings built in or before 1990
- **Data Quality**: Only buildings with valid coordinates

## Responsive Features:

- **Desktop**: Full statistics panel visible on the left
- **Tablet**: Panel adapts to screen size
- **Mobile**: Panel can be folded to a small bar to maximize map visibility
- **Fold/Unfold**: Click the chevron button to hide/show the control panel

## Data Source:

The map uses NYC Open Data including:
- PLUTO (Property Land Use Tax Lot Output) for building information (office and industrial buildings)
- ACRIS (Automated City Register Information System) for financing data with document categorization (Mortgage/Deed)
- NYC Department of City Planning for district boundaries
- ZOLA (Zoning and Land Use Application) for property details and zoning information
- **NEW: Street centerline data** for corner lot analysis
- **NEW: Building footprint analysis** for depth and frontage calculations

## Technical Notes:

- The map is self-contained and doesn't require internet connection
- All data is embedded in the HTML file
- Compatible with modern web browsers (Chrome, Firefox, Safari, Edge)
- No installation or setup required
- Responsive design works on all screen sizes
- Control panel can be collapsed to maximize map visibility
- **NEW: CSV download functionality** for data export
- **NEW: Enhanced building metrics** with conversion analysis

## Data Summary:

- **Total Buildings**: 306 (filtered from original dataset)
- **Geographic Coverage**: Community District 4 OR Council District 3
- **Size Filter**: ≥ 100,000 square feet
- **Age Filter**: Built in or before 1990
- **Data Fields**: 39 columns including financial, conversion analysis, and vacancy data

Generated: August 20, 2025 