# Manifold Scoop Bucket [![Build status](https://ci.appveyor.com/api/projects/status/xptg33rud6mfr2pg/branch/master?svg=true)](https://ci.appveyor.com/project/rkolka/scoop-manifold/branch/master)

Bucket for [Scoop](http://scoop.sh) containing manifests for [Manifold](http://manifold.net) software.

Manifold 9 is powerful parallel GIS, ETL, data science and DBMS tool.

## Usage example

To make it easier to install apps from this bucket, run

$ `scoop bucket add manifold-bucket https://github.com/rkolka/scoop-manifold.git`

The name `manifold-bucket` can be anything. You may change it.

### Check available versions

$ `scoop search manifold`

manifold-bucket bucket:

- manifold-edge (9.0.175.4)
- manifold-stable-bundle (9.0.175)
- manifold-stable (9.0.175)
- manifold-viewer-edge (9.0.175.4)
- manifold-viewer-stable (9.0.175)
- manifold-xtra-bundle (9.0.175.4)

### Install desired version

$ `scoop install manifold-edge`

## Descriptions

### manifold-edge (9.0.175.4) :+1: **Recommended.**

Manifold 9 is powerful parallel GIS, ETL, data science and DBMS tool. Cutting Edge builds are issued monthly or semimonthly.

### manifold-stable (9.0.175)

Official build of Manifold 9. Manifold official builds are issued about every 4-6 months.

### manifold-viewer-edge (9.0.175.4) ***Free viewer!*** :+1: **Recommended.**

Manifold Viewer is the free, read-only version of Manifold Release 9 - a GIS, ETL, data science and DBMS tool. Cutting Edge builds are issued monthly or semimonthly.

### manifold-viewer-stable (9.0.175) ***Free viewer!***

Official build of Manifold Viewer. Manifold official builds are issued about every 4-6 months.

### manifold-stable-bundle (9.0.175)

Official build Manifold 9 + optional third-party software. This package includes third-party libraries that provides IronPython scripting and MySQL, PostgreSQL/PostGIS, and SQLite drivers. It also includes 233 MB grids.dat for coordinate transformations.

### manifold-xtra-bundle (9.0.175.4)

Cutting Edge build of Manifold 9 + custom experiments. May change unexpectedly.
