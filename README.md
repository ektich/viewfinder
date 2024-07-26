# View Finder Reimplemented

The idea of this project is to generate a view from any point on earth, looking in any direction. It is a re-implementation of the [Viewfinder Panoramas](https://www.viewfinderpanoramas.org/) by Jonathan de Ferranti.

## Quick start
 - make sure you have GNU Make and CLANG compiler installed
 - compile the code using "make main" command
 - run the code with "./main > output.ppm"

Rendered image of a sphere should be saved in the `output.ppm` file.

## Ray Tracing
Ray tracing code is based on the [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html) tutorial by Peter Shirley, Trevor David Black and Steve Hollasch.

## DEM model
Eventually, the NASADEM  will be used as the Digital Elevation Model. NASADEM data is avialiable in multiple formats. Most likely the HGT format is sufficient for this project.

## References
 - CR. Steger, B. Steger, C. Shär "HORAYZON v1.1: An efficient and flexible ray-tracing algorithm to compute horizon and sky view factor" https://www.viewfinderpanoramas.org/)
 - Viewfinder Panoramas: https://www.viewfinderpanoramas.org/
 - NASADEM: [NASA EarthData Search Link](https://search.earthdata.nasa.gov/search/granules?p=C2763264762-LPCLOUD&pg[0][v]=f&pg[0][gsk]=-start_date&fi=SRTM&fdc=Land%2BProcess%2BDistributed%2BActive%2BArchive%2BCenter%2B%2528LPDAAC%2529&tl=1721973902.491!3!!)