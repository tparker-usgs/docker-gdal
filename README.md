docker-gdal
============

A docker image to isolate the GDAL build. Use by putting something like this in your Dockerfile:
  COPY --from=tparker/docker-gdal /usr/local /usr/local
 
