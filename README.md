
# CODEX Single Cell Multiplexed Imaging Analysis using Clustergrammer2

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ismms-himc/codex_dashboard/master?urlpath=voila%2Frender%2Findex.ipynb)

<img src='img/codex_screenshot.png' alt="CODEX Example" width="800px" >

[Goltsev et al](https://linkinghub.elsevier.com/retrieve/pii/S0092867418309048) used a highly multiplexed cytometric approach called CODEX to measure ~30 surface markers in spatially resolved single cells from mouse spleens. We utilized Clustergrammer2 to hierarchically cluster ~5,000 sinlge cells (from a subset of a segmented spleen image). We also used the Jupyter Widget [bqplot](https://github.com/bloomberg/bqplot) to visualize single cell location data using voronoi plots. We then built a dasnboard using the library [voila](https://github.com/QuantStack/voila), which converts Jupyter notebooks to dashboards/web-apps, and linked our heatmap to the spatial map. This allows to interact with the Clustergrammer2 heatmap and highlight cells in the spatially resolved map. These kind of linked views are crucial for exploration of spatially resolved high-dimensional single cell data. Finally, we are running this dashboard using MyBinder. 

### YouTube Tutorial
[![10K PBMC CITE-seq](http://img.youtube.com/vi/JlUvt4rpF-s/0.jpg)](http://www.youtube.com/watch?v=JlUvt4rpF-s)

CODEX data from: http://welikesharingdata.blob.core.windows.net/forshare/index.html

Voila dashboard example originally from: https://github.com/voila-gallery/gaussian-density

Note: works best in Chrome Browser.
