# pilot-reference
Generates a simple poster containing useful information:
[Check it out here](https://ni2be.github.io/pilot-reference/)

## How to use?

### Finding Airports
1. **Set your search area**: Click on the map (or use the place search) to select the center point for your region
2. **Adjust the radius**: Use the radius input to set the search distance in kilometers
3. **Find nearby airports**: Click "Find Nearby" to load all airports within the specified radius

### Filtering & Customization
4. **Filter by type**: Check/uncheck airport types (large, medium, small, heliport, seaplane, balloon, closed) to show only what you need
5. **Interactive map**:
   - Color-coded markers show all selected airports on the map
   - Click a marker to highlight and scroll to that airport in the grid
   - Click an airport card to pan and pulse its marker on the map
6. **Reorder airports**: Drag and drop airport cards to customize the order
7. **Remove airports**: Click the "×" button on any airport card to remove it from your selection

### Manual Editing
8. **Edit JSON directly**: Modify the JSON in the text area to add/remove airports, navigation markers or to fix missing altitude data
9. **Apply changes**: Click "Apply" to update the grid and map with your manual edits
   - Note: Type filters remain active and will hide airports not matching your filter
   - Hidden airports are preserved and won't be lost when you edit visible airports
   - Warning: Using "Find Nearby" will replace your manual selections

### Data Updates
- Airport data is automatically updated every Sunday from [OurAirports.com](https://ourairports.com)
- The dataset includes worldwide airports with coordinates, types, and elevation data

<img width="795" height="1240" alt="image" src="/docs/image.png" />

