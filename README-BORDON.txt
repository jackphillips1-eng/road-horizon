ROAD HORIZON — BORDON ROAD MATCHING ALPHA

TEST AREA
Bordon, Hampshire — approximately 6 km radius around the town centre.

WHAT THIS BUILD DOES
• Displays an interactive Leaflet/OpenStreetMap map centred on your live GPS location.
• Shows a live user-location marker and GPS accuracy circle.
• Lets you pan, pinch-zoom and return to your location with the locate button.
• Downloads an actual local road network from OpenStreetMap via Overpass.
• Caches that network on your device after the first successful load.
• Records real iPhone GPS points.
• Finds the nearest plausible road segment for each usable GPS fix.
• Marks matched segments as completed and stores completion locally.
• Colours completed segments green on the Bordon map.
• Colours segments from the current drive amber until the drive is stopped.
• Calculates a genuine local completion percentage by segment mileage.
• Shows the currently matched road name/reference.
• Counts road ways encountered during the current drive.
• Car and Bike modes contribute to the same completion.
• Preserves Home, Progress, Achievements, Profile, Pro preview and existing device data.

ALPHA NOTES
This is intentionally a local proof-of-concept. GPS can occasionally snap to the wrong
parallel or nearby road, especially at junctions or when accuracy is poor. The matching
algorithm will be hardened after real-world testing.

Road data © OpenStreetMap contributors, available under the Open Database License (ODbL).
https://www.openstreetmap.org/copyright

GITHUB PAGES UPDATE
1. Extract the supplied ZIP.
2. Open the road-horizon repository on GitHub.
3. Choose Add file → Upload files.
4. Upload every extracted file to the repository root and replace matching files.
5. Commit the changes to main and wait for GitHub Pages to redeploy.
6. Fully close and reopen the home-screen app. If the previous map remains cached,
   reopen once more after a minute; this release uses a new PWA cache version.

On the first visit to Map, choose Allow While Using App when location permission is requested.
