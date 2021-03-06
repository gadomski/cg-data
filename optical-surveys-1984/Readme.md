# Optical Surveys (1984)

Preview this [Data Package](http://specs.frictionlessdata.io/data-packages/) using the [Data Package Viewer](http://data.okfn.org/tools/view?url=https://raw.githubusercontent.com/ezwelty/cg-data/master/optical-surveys-1984).

## Citation

> Bruce H. Vaughn, Charlie F. Raymond, Lowell A. Rasmussen, D. S. Miller, C. A. Michaelson, Mark F. Meier, Robert M. Krimmel, Andrew G. Fountain, William W. Dunlap, and C. S. Brown (1985). Short-Term Velocity Measurements at Columbia Glacier, Alaska; August-September 1984. U.S. Geological Survey Open File Report 85-487. Retrieved from https://pubs.er.usgs.gov/publication/ofr85487.

Abstract

> Ice velocity data are presented for the lower reach of Columbia Glacier, Alaska. The data span a 29 day period and contain 1,072 angle sightings from two survey stations to 22 markers placed on the ice surface, and 1,621 laser measurements of the distance to one of those markers (number 11) from another station. These short-interval observations were made to investigate the dynamics of the glacier and to provide input to models for estimation of future retreat and iceberg discharge. The mean ice velocity (at marker number 11) was approximately 9 m/day and ranged from 8 to >15 m/day. The data set includes a well defined 2-day, 50% velocity increase and a clear pattern of velocity fluctuations of about 5% with approximately diurnal and semi-diurnal periods.

## Analog-Digital Conversion

The scanned copy of the report ([vaughn-others-1985.pdf](sources/vaughn-others-1985.pdf)) was downloaded from the [USGS Publications Warehouse](https://pubs.er.usgs.gov/publication/ofr85487). The data in Table 1 ([vaughn-others-1985-table-1.csv](sources/vaughn-others-1985-table-1.csv)), Appendix 1 ([vaughn-others-1985-appendix-1.csv](sources/vaughn-others-1985-appendix-1.csv)), and Appendix 2 ([vaughn-others-1985-appendix-2.csv](sources/vaughn-others-1985-appendix-2.csv)) were extracted with [tabula](https://github.com/tabulapdf/tabula) and reshaped with [atom](https://github.com/atom/atom), then checked visually overlaid on the original report using Adobe Illustrator.

## To Do

- Convert original elevations (relative to local sea level) to height above the WGS84 ellipsoid.
- Extract meteorologic and hydrologic data ([driedger-others-1988.pdf](sources/driedger-others-1988.pdf)).
- (as needed) Extract ice ablation and precipitation (krimmel-vaughn-1987.pdf, Figure 6).
- (as needed) Extract insolation at MET, river stage at GATE, air temperature at GATE, precipitation at MET (walters-dunlap-1987, Figure 3).
