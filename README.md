<h1 align="center">ODM</h1>
<h4 align="center">Open data for Mississippi</h4>

<p align="center">
  <img src="https://img.shields.io/badge/open-education-green.svg?style=for-the-badge">
</p>

# Open map data for Mississippi public school districts

Converted from Maris .shp data using gdal.

## Why

Because we need district data for cool apps...and not everyone is a GIS analyst.

## Quickstart

To access the actual file, go to/copy [this link](https://github.com/davidbkay/mississippi-education-geojson/blob/c0af6a8c41beca12808ad88367fb6b7bea322126/districts-mississippi.geojson).

## Accessing programatically

You can link directly to this file for any mapping needs.

https://cdn.jsdelivr.net/gh/davidbkay/mde-open-data@0.0.1/mississippi-districts.geojson

```python
# Pandas
df=pd.read_json('https://cdn.jsdelivr.net/gh/davidbkay/mde-open-data@0.0.1/mississippi-districts.geojson')
```

> way more to come

-dk
