[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10668908)
# Python Programming with Rasterio
## Assignment
In this assignment you will learn about the `rasterio` library and interact with Sentinel scenes in an AWS cloud bucket. You will also learn about Cloud-Optimized Geotiffs (COGs) and the Spatio-Temporal Asset Catalog (STAC) specification.

## Background
You have learned how to use the `geopandas` library to interact with geospatial vector data. The next step is to interact with raster data. The primary library that we use for raster is `rasterio`.Due to the nature of raster datasets and, in large part because of continous earth observation from satellites, a number of standards and technologies have built around optimizing finding raster datasets and utilizing subsets of raster datasets without necessitating the download of copious amounts of imagery that end users have no interest in. The main concepts we will talk about here are Cloud-Optimized Geotiffs, or COGs, windowed reads, and the Spatio-Temporal Asset Catalog (STAC) standard for searching for satellite imagery and other spatio-temporal data.

Background reading:
- COGs
  - https://developers.planet.com/docs/planetschool/an-introduction-to-cloud-optimized-geotiffs-cogs-part-1-overview/
- Rasterio
  - Windows Reading: https://rasterio.readthedocs.io/en/latest/topics/windowed-rw.html
- STAC
  - Intro to STAC: https://stacspec.org/en/tutorials/intro-to-stac/
  - About STAC: https://stacspec.org/en/about/stac-spec/ 

## Housekeeping
### Learning Objectives
1) Become familiar with python libraries: `rasterio` and `satsearch`.
2) Learn about Cloud-Optimized Geotiffs (COGs)
3) Learn about Spatio-Temporal Asset Catalogs (STACs)

## Get started with your codespace
This assignment will be conducted through your codespace for this repo. 

1) Create a new branch, `rasterio`
2) Create a special codespace (see instructions below). If you don't select a larger machine type the codespace will crash on start and enter recovery mode.
The default codespace machine type does not have enough disk space to run this assignment so you will need to select a larger machine type.
Click on the "Code" icon and select the hamburger icon (...) to open a dialog to create a new codespace with options:

   ![codespace-hamburger](./media/codespace-hamburger.png)

Next, change the machine type to `16-core`:

 ![codespace-machine-type](./media/codespace-machine-type.png)

Finally, click "Create codespace"

It will take several minutes for this codespace to be created because it is custom and needs to build itself first.

4) The instructions for the assignment can be found in the Jupyter Notebook, `assignment.ipynb`.

## Deliverables
Submit a pull request to merge your `rasterio` branch with `master` (but do not merge). The `rasterio` branch should include:
- `stac-items.png`
- `image-numpy.png`
- `image-plots.png`
- `fields.png`
- `ndvi-time-series.png`
