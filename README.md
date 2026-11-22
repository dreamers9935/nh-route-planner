# NH Route Planner

A one-page tool for FASTag **Annual Pass** holders. You enter a source and a destination, and it:

1. compares OSRM route alternatives, scoring each by how much of it is on a National Highway (NH/NE) and steering away from state-run toll expressways (UPEIDA and similar), where the pass is not valid;
2. places 5–9 stops in the middle of long NH stretches, away from towns and junctions;
3. builds a shareable Google Maps navigation link with those stops as waypoints;
4. looks up the toll plazas on the route (OpenStreetMap / Overpass) and marks whether each one is on an NH.

Shareable link format: `?from=<source>&to=<destination>&n=<stops>`

Data comes from OpenStreetMap, Nominatim, OSRM and Overpass, so it may be incomplete. Check plazas in NHAI's Rajmargyatra app before a long trip.
