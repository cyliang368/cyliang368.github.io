---
title: "Parallel computing in GIS"
excerpt: "Parallel computing speeds up programs, allowing the usage of large-scale and high-resolution data in a reasonable time.
<br/><img src='/images/portfolio/grass/rhorizon_raster_speedup.png' style='display: inline-block; width: 49%; margin-right: 1%;'>
<img src='/images/portfolio/grass/rhorizon_raster_efficiency.png' style='display: inline-block; width: 49%;'>"
collection: portfolio
---

With the advancement of satellite and remote sensing technologies, access to large-scale, high-resolution geospatial data has significantly increased. I am an active contributor to the development team of GRASS GIS, an open-source geospatial software system. My work focuses on parallelizing tools, enhancing benchmark modules, and implementing unit tests to optimize performance. Notably, during the GRASS Community Meeting in the summer of 2024, I successfully parallelized several widely used tools, including <i>r.horizon</i>, <i>v.surf.rst</i>, and <i>r.texture</i>, using OpenMP, improving the efficiency and scalability of these functions on CPU. I am currently working on accelerating computations on GPU using OpenACC.

Selected pull request: <br/>
[r.horizon: Support parallel computing for the raster mode by OpenMP #3890](https://github.com/OSGeo/grass/pull/3890) <br/>
[r.texture: support parallel computing by OpenMP #3857](https://github.com/OSGeo/grass/pull/3857) <br/>
[v.surf.rst: Cross-validation OpenMP support #3590](https://github.com/OSGeo/grass/pull/3590) <br/>

<br/><img src='/images/portfolio/grass/2024_community_meeting_collage.png'>
[Report from the GRASS Community Meeting 2024](https://grass.osgeo.org/news/2024_08_02_report_community_meeting_prague_2024/)