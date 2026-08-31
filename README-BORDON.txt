ROAD HORIZON — BORDON ROAD MATCHING ALPHA

TEST AREA
Bordon, Hampshire — approximately 6 km radius around the town centre.

WHAT THIS BUILD DOES
• Gives Car and Bike their own verified road-completion layers.
• Adds Combined, Car and Bike map filters with distinct road colours.
• Uses green for Car, blue for Bike and gold when a road is completed in both modes.
• Shows separate Bordon completion percentages and verified mileage for each mode.
• Keeps Combined as the protected union used by overall progress and achievements.
• Migrates past journey records into the correct mode when their saved journey mode is known.
• Retains any older unclassified road credit safely in Combined without guessing its mode.
• Locks the mode selector while tracking so one journey cannot change mode part-way through.
• Removes false matches only from the journey’s mode layer while preserving valid credit elsewhere.
• Removes GPX-import references: road credit cannot be added or imported manually.
• Adds all 113 UK county-level areas under Progress with nation filtering.
• Shows completion percentage, completed/total mileage, completed/total roads and a progress bar.
• Keeps Bordon’s verified result separate as a pilot, rather than presenting it as Hampshire-wide.
• Displays areas awaiting national road data honestly at 0.0%.
• Connects future verified area progress to the matching county awards automatically.
• Expands Awards to exactly 50 core achievements, including 10% completion steps to 100%.
• Adds 113 county-level completion awards across all four UK nations.
• Uses 48 English ceremonial counties, 22 Welsh principal areas,
  32 Scottish council areas and 11 Northern Irish local-government districts.
• Adds mobile filters for Core, Completion and County & Area awards.
• Awards are calculated from verified app data; there is no manual unlock control.
• Makes every landmark collectible tappable with a concise point-of-interest overview.
• Shows landmark name, location, significance, discovery status and collection rule.
• Standardises every landmark GPS discovery boundary to a 100-metre radius.
• Adds a post-drive journey review with route map, distance, time and match confidence.
• Requires continued GPS evidence before a road segment receives completion credit.
• Suppresses one-fix side-road snaps commonly seen while passing junctions.
• Allows false matches to be removed, but provides no way to add or approve road completion.
• Adds recent journey reviews to the Progress tab.
• Adds GPS-discovered landmark collectables to the Awards tab.
• Starts with four meaningful Bordon-area places and eight major UK icons.
• Saves collected landmarks on the device and displays them as pins on the map.
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
• Car and Bike contribute to Combined progress while retaining separate mode records.
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
