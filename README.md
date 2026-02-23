# Forgotten Realms Rasters (Georeferenced)

This repository contains a collection of georeferenced raster maps for the Forgotten Realms. These assets provide the essential spatial baseline for the [Toril GIS](https://github.com/geospatial-grimoire/toril-gis) project and are shared to empower the fantasy cartography community in crafting lore-accurate, spatially consistent maps.

## Technical Specifications

All rasters in this repository are anchored using the [Toril Geographic Coordinate System (GCS)](https://www.geospatial-grimoire.com/blog/2024-11-09-crafting-coordinate-systems-for-faerun-and-beyond/). Where required, controlled distortions have been applied to rectify artistic source maps for a seamless fit within the global coordinate system.

### Georeferencing Standards
- **TIFF Files (.tif):** These are provided as **GeoTIFFs**. The spatial metadata and coordinate system information are embedded directly within the file header.
- **PNG & JPG Files:** These images are accompanied by **World Files (.pgw and .jgw)**. This is a standardized sidecar file format that contains the necessary transformation parameters (scale, rotation, and coordinates) to position the imagery correctly in geospatial software.

### Usage Instructions

#### Option A: Native Toril GCS (Recommended)
For the highest accuracy in **QGIS, ArcGIS, or other GIS software**, define the custom Toril GCS coordinate system using the WKT-CRS format found in [Toril GIS Resources](https://github.com/geospatial-grimoire/toril-gis/blob/main/resources/crs/toril_gcs.wkt).

#### Option B: WGS84 Workaround
If your software does not support custom coordinate systems, you could forcibly assign **WGS84 (EPSG:4326)** to these files. While the maps will load and be generally usable, please be aware that minor distortions or misalignments may occur compared to the native Toril GIS environment.

---

## Map Inventory

### 1. Forgotten Realms Atlas (FRA - 1990)
*Scans from the original 2nd Edition Atlas*

![Forgotten Realms Atlas (FRA - 1990) - Georeferenced Maps](resources/forgotten-realms-georeferenced-fra-maps.jpg)

- `FRA (1990) - Eastern Realms - Hearthlands 1.png`
- `FRA (1990) - Eastern Realms - Hearthlands 2.png`
- `FRA (1990) - Eastern Realms - North 1.png`
- `FRA (1990) - Eastern Realms - North 2.png`
- `FRA (1990) - Eastern Realms - South 1.png`
- `FRA (1990) - Eastern Realms - South 2.png`
- `FRA (1990) - Eastern Realms - Southwest 1.png`
- `FRA (1990) - Eastern Realms - Southwest 2.png`
- `FRA (1990) - Hordelands 1.png`
- `FRA (1990) - Hordelands 2.png`
- `FRA (1990) - Moonshae Isles 1.png`
- `FRA (1990) - Moonshae Isles 2.png`
- `FRA (1990) - Western Realms - Northeast 1.png`
- `FRA (1990) - Western Realms - Northeast 2.png`
- `FRA (1990) - Western Realms - Northwest 1.png`
- `FRA (1990) - Western Realms - Northwest 2.png`
- `FRA (1990) - Western Realms - Southeast 1.png`
- `FRA (1990) - Western Realms - Southeast 2.png`
- `FRA (1990) - Western Realms - Southwest 1.png`
- `FRA (1990) - Western Realms - Southwest 2.png`

### 2. Forgotten Realms Interactive Atlas (FRIA - 1999)
*The primary baseline for continental and regional mapping (2nd Edition)*

![Forgotten Realms Interactive Atlas (FRIA - 1999) - Georeferenced Maps](resources/forgotten-realms-georeferenced-fria-maps.jpg)

**Global & Continental (Levels 0-1):**
- `FRIA (1999) - Lvl 0 - A1.png` / `A2.png` / `D.png` / `D1.png`
- `FRIA (1999) - Lvl 1 - B1alc.png`, `B1blc.png`, `B1clc.png`, `B1dlc.png`
- `FRIA (1999) - Lvl 1 - B2alc.png`, `B2clc.png`
- `FRIA (1999) - Lvl 1 - C1alc.png`, `C1clc.png`
- `FRIA (1999) - Lvl 1 - C2alc.png`

**Regional Quads (Levels 2-3):**
- `FRIA (1999) - Lvl 2 - B1cNorth.png`, `B1cSouth.png`
- `FRIA (1999) - Lvl 3 - B1aSElc.png`, `B1aSWlc.png`, `B1cNElc.png`, `B1cNWlc.png`, `B1cSElc.png`, `B1cSWlc.png`
- `FRIA (1999) - Lvl 3 - B1dNElc.png`, `B1dNWlc.png`, `B1dSElc.png`, `B1dSWlc.png`
- `FRIA (1999) - Lvl 3 - B2aNElc.png`, `B2aNWlc.png`, `B2bNElc.png`, `B2bNWlc.png`, `B2bSElc.png`, `B2bSWlc.png`, `B2dNElc.png`, `B2dNWlc.png`
- `FRIA (1999) - Lvl 3 - C1aSElc.png`, `C1aSWlc.png`, `C1cNElc.png`, `C1cNWlc.png`, `C1cSElc.png`, `C1cSWlc.png`
- `FRIA (1999) - Lvl 3 - C2aNElc.png`, `C2aNWlc.png`, `C2aSElc.png`, `C2aSWlc.png`
- `FRIA (1999) - Lvl 3 - Mazticalc.png`

**Detail Maps (Level 4):**
- `Bawalc.png`, `Cormyr.png`, `Evermeetlc.tif`, `Lantan.png`, `Moonsea.png`, `Moonshaeslc.png`, `Nelantherlc.png`, `Nimbral.png`


### 4. Modern WotC

- `WotC - Scholar's view 2001_3E.png`
- `WotC - Faerun_3E.tif`
- `WotC - Faerun Political_3E.tif`
- `WotC - Cordell Underdark 2003_3E.tif`
- `WotC - Faerun Map 2008_4E.png` (note that geographically 4E is so radically different that a meaningful alignment is impossible)
- `WotC - Sword Coast Map 2015_5E.tif` (5th Edition standard)

### 5. Community
- `AIF (2020) - Faerun_v2.jpg` (by Adam Whitehead - [Atlas of Ice & Fire](https://atlasoficeandfireblog.wordpress.com/))
- `AIF (2023) - Toril.png` (by Adam Whitehead - [Atlas of Ice & Fire](https://atlasoficeandfireblog.wordpress.com/))

---

## Wizards of the Coast Fan Content Policy
This project is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.

All materials are provided for non-commercial, educational, and hobbyist use.