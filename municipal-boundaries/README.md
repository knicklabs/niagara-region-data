# Niagara Region Municipal Boundaries

<script src="https://embed.github.com/view/geojson/knicklabs/niagara-region-data/master/municipal-boundaries/municipal-boundaries.topojson"></script>

The data in this directory was obtained from the [Niagara Region Open Data Pilot program](http://www.niagararegion.ca/government/opendata/default.aspx). The data was obtained as a shape file and converted to GeoJSON using [GDAL](http://www.gdal.org). [TopoJSON](https://github.com/mbostock/topojson) files were then created from the GeoJSON files. The [original shape file](http://www.gdal.org) can be downloaded directly from the [Municipal Boundaries data set](http://www.niagararegion.ca/government/opendata/data-set.aspx#id=13&tab=data_table&f=xml&r=25&p=1).

The source shape file was downloaded, adapted, and published in accordance with the license provided through the Niagara Region Open Data Pilot program. The license may be [viewed online](http://www.niagararegion.ca/government/opendata/terms-of-use.aspx). A copy of this license is stored in the LICENSE.txt file in this directory for reference. Please understand that if you use this data, you will be bound to the same terms.

Due to the large size of the converted file (muncipal-boundaries.json), I have split the file up into several smaller files - one file for each municipality.
