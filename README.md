# SHiELD_container
Containerized SHiELD (System for High-resolution prediction on Earth-to-Local Domains), a atmosphere model for weather-to-seasonal prediction.

Visit [SHiELD in a box](https://shield.gfdl.noaa.gov/shield-in-a-box/) for more information.

## Prerequisite
`Git and Docker`

## Get the prebuild Docker image
`docker pull gfdlfv3/shield`

## Build your own image (Optional)
- Download Dockerfile

- Compile model:
`docker build -it image_name .`

## Proper usage attribution
Cite [Cheng et al. (2022)](https://doi.org/10.5194/gmd-15-1097-2022) and [Harris et al. (2020)](https://doi.org/10.1029/2020MS002223) when describing the containerized SHiELD.
