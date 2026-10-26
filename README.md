# EHF Service Waste Map

Interactive map of oil and gas waste sites in the Episcopal Health Foundation's 80-county service area, from Texas Railroad Commission records through Aug. 31, 2026.

**Layers** (each can be switched on or off):

| Layer | Source | Sites |
|---|---|---|
| Solid Waste Pit | Active Schedule A pit registrations | 995 |
| Produced Water Pit | Active Schedule B pit registrations | 8 |
| CWD Facility | Approved commercial pits, stationary treatment, reclamation (R9), landfarm, land application and land treatment permits (EPS) | 96 |
| CWD Facility (permit upcoming) | New applications pending as of Aug. 31, 2026 | 7 |
| CWD Facility (renewal pending) | Renewal applications pending as of Aug. 31, 2026 | 23 |

Clicking a CWD site lists every EPS permit at that facility, including hydrostatic test and minor permits.

**Notes**
- Service area counties come from the data behind EHF's [service area map](https://www.episcopalhealth.org/who-we-are/about/our-service-area-map/). Its caption says 81 counties; 80 are listed and used here.
- Nine pits whose filed coordinates fall outside the service area are not shown. Seven sites whose coordinates fall in a different county than the one listed carry a warning in their popup.
- Two approved CWD sites have no coordinates on file and are not shown.

Files: `index.html` (the map) and `data.json` (the points).
