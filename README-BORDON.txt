ROAD HORIZON — HAMPSHIRE & SURREY REGIONAL ALPHA

ENABLED AREA
Drive-ready road matching across Hampshire and Surrey, with the original Bordon
area retained as the stable local completion pilot.

WHAT THIS BUILD DOES
• Expands drive-ready road matching from Bordon to Hampshire and Surrey.
• Supports motorways, link/slip roads, trunk, primary, secondary, tertiary,
  unclassified, residential, living-street, service and generic road classifications.
• Loads all supported roads in small geographic tiles around live GPS or the map centre.
• Loads a new tile automatically as the user travels or pans at road-detail zoom.
• Preloads an adjacent tile when the user approaches a tile edge.
• Stores downloaded regional road tiles in IndexedDB for later journeys and offline reuse.
• Uses stable OpenStreetMap way-and-segment IDs so existing completion remains valid.
• Deduplicates roads that cross tile edges or appear in the original Bordon seed data.
• Shows active county tile, cached tile count and loaded road count on the Map screen.
• Includes a manual refresh for the current Hampshire or Surrey map area.
• Avoids a single county-wide Overpass request that would be unreliable on a phone.
• Adds a working Road Hunter across loaded Hampshire and Surrey road tiles.
• Finds the nearest suitable unfinished road from the user’s live GPS position.
• Searches Combined, Car or Bike completion independently.
• Avoids prioritising anonymous service roads when ordinary unfinished roads are available.
• Shows the target road, road type, straight-line distance and target status.
• Offers alternative nearby targets with a Next Option control.
• Highlights the selected road and target point on the live map.
• Passes the target into Drive while leaving the user in control of starting GPS tracking.
• Updates distance continuously as the live location changes.
• Marks the target reached only after the existing road matcher confirms live GPS evidence.
• Gives no completion credit for selecting, viewing or loading a Road Hunter target.
• Keeps Road Hunter honest about the currently loaded regional tiles.
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
• Downloads real regional road data from OpenStreetMap via bounded Overpass queries.
• Caches each successful road tile on the device.
• Records real iPhone GPS points.
• Finds the nearest plausible road segment for each usable GPS fix.
• Marks matched segments as completed and stores completion locally.
• Colours completed segments by Car, Bike and Both on the regional map.
• Colours segments from the current drive coral until the drive is stopped.
• Calculates a genuine local completion percentage by segment mileage.
• Shows the currently matched road name/reference.
• Counts road ways encountered during the current drive.
• Car and Bike contribute to Combined progress while retaining separate mode records.
• Preserves Home, Progress, Achievements, Profile, Pro preview and existing device data.

ALPHA NOTES
This is intentionally a regional proof-of-concept. GPS can occasionally snap to the wrong
parallel or nearby road, especially at junctions or when accuracy is poor. The matching
algorithm will be hardened after real-world testing. Hampshire and Surrey county completion
is not calculated from partially loaded tiles; it remains pending until a full denominator
manifest is available, preventing misleading whole-county percentages.

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
