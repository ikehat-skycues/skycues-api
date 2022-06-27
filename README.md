# skycues-api

SkyCues is a satellite and aerial image enhancement service, capable of recovering hidden details.
The service employ multiple technologies, including super-resolution, dynamic intelligent color-correction, and more.

The main capabilities of the SkyCues systems are:

* Enhancing images to x4 the source pixel size (so a 1m/pixel source produces 25cm/pixel enhancement)
* Compatible with most satellite and aerial RGB sources 15cm to 15m
* Sentinel-2 specific capabilities: RGB+NIR x4 to produce high-res indexes like NDVI, Intelligent color-correction, production by AOI and date
* Coming up: georeferencing correction to the enhanced resolution, matching Google Maps as a base map

Disclaimer: the enhanced image is not identical to an optical image at the same resolution, much like pansharpened images interpolate lower-resolution multispectral data to match a higher-resolution panchromatic band.

You need to register as a subscriber at https://skycues.com, where you will get an API key.

The API documentation is available at https://skycues.com/api-docs/

Node and Python sample code is available in this repo.
