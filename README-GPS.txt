ROAD HORIZON — GPS BUILD 1

What changed
- Start Drive now requests real device location.
- Uses high-accuracy Geolocation watchPosition while the web app remains active.
- Calculates travelled distance from GPS points.
- Shows GPS accuracy and recorded point count.
- Saves up to 50 completed drives locally on the device using localStorage.
- Car/Bike mode is stored with each drive.
- New Roads remains blank for now: road-network map matching is the next milestone.

Important iPhone limitation
A browser/PWA cannot be relied upon for continuous long-duration background GPS tracking
after iOS suspends it or the screen is locked. This build is ideal for proving the tracking
logic. A production-grade Road Horizon tracker may ultimately need a native iOS wrapper/app
for dependable background tracking.
