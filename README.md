# Hell's Kitchen Building Map Package

This package contains an interactive map of Hell's Kitchen buildings with financing data.

## Files Included:

- **hells_kitchen_map.html** - The main interactive map file
- **hells_kitchen_financing_report_20250718_202842.csv** - Building data used in the map
- **input/** - Shapefile data for district boundaries
  - HellsKitchen.* - Hell's Kitchen boundary
  - CouncilDistrict.* - Council District boundary  
  - communityBoard.* - Community Board 4 boundary

## How to Use:

1. **Open the map**: Double-click `hells_kitchen_map.html` to open it in your web browser
2. **Navigate**: Use mouse to pan and zoom around the map
3. **View buildings**: Click on building markers to see detailed information
4. **Toggle boundaries**: Use the "Fill Boundaries" control on the right side
5. **View statistics**: Building statistics are displayed on the left side

## Map Features:

- **Building Markers**: 
  - Green markers = Buildings with financing documents
  - Red markers = Buildings without financing data
- **District Boundaries**: 
  - Red = Hell's Kitchen
  - Orange = Council District
  - Purple = Community Board 4
- **Interactive Controls**: Toggle boundary fills, view statistics
- **Background Options**: Switch between different map backgrounds

## Data Source:

The map uses NYC Open Data including:
- PLUTO (Property Land Use Tax Lot Output) for building information
- ACRIS (Automated City Register Information System) for financing data
- NYC Department of City Planning for district boundaries

## Technical Notes:

- The map is self-contained and doesn't require internet connection
- All data is embedded in the HTML file
- Compatible with modern web browsers (Chrome, Firefox, Safari, Edge)
- No installation or setup required

Generated: July 18, 2025 