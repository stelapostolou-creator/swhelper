# SWHelper

**SW Maps → any coordinate system (EPSG)** — an offline-capable web app (PWA) for surveyors.

By **Stylianos F. Apostolou**, Surveying Engineer — Zitsa, Ioannina, Greece
📧 stel.apostolou@gmail.com

## What it does

- Opens **SW Maps** databases (`.swm2`) and Excel exports — points, lines, polygons with correct geometry
- Reprojects to **any EPSG code** (UTM zones and WGS84 work fully offline; other codes fetched from epsg.io)
- **Stakeout tools**: extend beyond a line, densify at a fixed step, distance intersection (two circles)
- **Exports**: DXF (2D/3D polylines), TXT points per layer, stakeout CSV for SW Maps
- Works **offline** once installed — all libraries are bundled locally

## Install

Open the app URL on your phone → browser menu → *Add to Home screen*.

## Works with SW Maps

Designed to work hand-in-hand with **SW Maps** — the best entirely free field data collector.
Many thanks to developer **Avinab Malla** of **Aviyaan Tech (P) Ltd.**, and to **Softwel (P) Ltd.** for publishing it.

- https://aviyaantech.com/swmaps/
- http://softwel.com.np/

## Tech

Plain HTML/CSS/JS — no build step. Bundled: Leaflet, proj4, sql.js, SheetJS.

---

© ZS-Top
