# leaflet-antarctic-demo

Demo of an interactive Antarctic map built with Leaflet and other open-source tools, using Spatial Reference System Identifier 3031.

This repo also hosted with GitHub pages at <https://thomasswilliams.github.io/leaflet-antarctic-demo/>.

Features:

- [Leaflet](https://leafletjs.com/) for interactive map functionality, zooming, panning (version 1.8, released April 2022)
- lightweight - a single HTML page, referencing javascript and CSS files from CDN
- Antarctic stereographic projection EPSG:3031 - see <https://spatialreference.org/ref/epsg/3031/>, <https://epsg.io/3031>
- well-commented HTML/javascript code :-)
- open-source OpenStreetMap/OpenMapTiles tiles from Global Biodiversity Information Facility (GBIF), see <https://tile.gbif.org/ui/>
- caching of tiles in-browser using <https://github.com/MazeMap/Leaflet.TileLayer.PouchDBCached>

See blog post at <> for more detail.

To host yourself, download this repo, and serve `index.html` (for instance, using Node module `http-serve` calling a command line like `http-server -o`).

Licensed under the [MIT license](LICENSE).