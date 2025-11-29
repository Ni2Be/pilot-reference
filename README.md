# pilot-reference
Generates a simple poster containing useful information:
[Check it out here](https://ni2be.github.io/pilot-reference/)

## How to use?

### Finding Airports
1. **Set your search area**: Click on the map (or use the place search) to select the center point for your region
2. **Adjust the radius**: Use the radius input to set the search distance in kilometers
3. **Add airports**: Click "Add Airports" to add all airports within the specified radius to your current list
   - Duplicates are automatically skipped
   - You can add airports from multiple regions by changing the center and clicking "Add Airports" again
4. **Clear all**: Click "Clear All" to remove all airports from your list and start fresh

### Filtering & Customization
5. **Filter by type**: Check/uncheck airport types (large, medium, small, heliport, seaplane, balloon, closed) to show only what you need
6. **Interactive map**:
   - Color-coded markers show all selected airports on the map
   - Click a marker to highlight and scroll to that airport in the grid
   - Click an airport card to pan and pulse its marker on the map
7. **Reorder airports**: Drag and drop airport cards to customize the order
8. **Remove airports**: Click the "×" button on any airport card to remove it from your selection

### Manual Editing
9. **Edit JSON directly**: Modify the JSON in the text area to add/remove airports, navigation markers or to fix missing altitude data
10. **Apply changes**: Click "Apply" to update the grid and map with your manual edits
   - Note: Type filters remain active and will hide airports not matching your filter
   - Hidden airports are preserved and won't be lost when you edit visible airports

### Data Updates
- Airport data is automatically updated every Sunday from [OurAirports.com](https://ourairports.com)
- The dataset includes worldwide airports with coordinates, types, and elevation data

<img width="795" height="1240" alt="image" src="/docs/image.png" />

