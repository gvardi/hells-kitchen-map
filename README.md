# Hell's Kitchen Building Map Package

This package contains an interactive map of Hell's Kitchen buildings with financing data.

## Files Included:

- **hells_kitchen_map.html** - The main interactive map file
- **hells_kitchen_financing_report_20250721_114540.csv** - Building data used in the map
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
5. **Responsive design**: The map adapts to different screen sizes automatically

## Map Features:

- **Building Markers**: 
  - Red building icons = Buildings without financing documents
  - Blue dollar signs = Buildings with mortgage financing
  - Purple dollar signs = Buildings with deed financing
  - Green dollar signs = Buildings with other financing types
- **District Boundaries**: 
  - Red = Hell's Kitchen
  - Orange = Council District
  - Purple = Community Board 4
- **Integrated Controls**: 
  - Statistics panel with fold/unfold functionality
  - Boundary fill toggle
  - Responsive design for mobile and desktop
- **Background Options**: Switch between different map backgrounds
- **ZOLA Links**: Click on building markers to view property details with direct links to NYC ZOLA records

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

## Technical Notes:

- The map is self-contained and doesn't require internet connection
- All data is embedded in the HTML file
- Compatible with modern web browsers (Chrome, Firefox, Safari, Edge)
- No installation or setup required
- Responsive design works on all screen sizes
- Control panel can be collapsed to maximize map visibility



Generated: July 21, 2025 