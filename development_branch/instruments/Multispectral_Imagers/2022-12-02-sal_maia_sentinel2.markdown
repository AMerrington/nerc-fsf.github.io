---
title: Maia- Sentinel 2 (S2) Multispectral Imager
layout: single
permalink: /instruments/atmospheric_equipment/SAL_Maia_S2
gallery1:
   - url: /assets/images/***
     image_path: /assets/images/***
gallery2:
   - url: /assets/images/***
     image_path: /assets/images/***
gallery3:
   - url: /assets/images/***
     image_path: /assets/images/***
sidebar:
   nav: "instruments"
classes: wide
toc: true
tags:
   - multispectral
   - UAV
   - agriculture
   - soil
   - vegetation
   - biomass
   - thermal
   - heat map
   - water stress

---
## Overview
The Maia S2 is a UAV mounted multispectral camera with the same wavelength intervals as ESA's Sentinel 2 satellite.

The Maia S2 has an array of 9 monochromatic 1.2MP sensors, each with band-pass filters within the VIS-NIR at the same wavelength intervals as Sentinel 2. It has a global shutter to ensure that each spectral layer has the same field of view.

{% include  gallery id = "gallery1"%}
{% include  gallery id = "gallery2"%}

## Where would you use this sensor? **Informal or 'Example applications'**
- Precision agriculture | Vegetation health
- Geological surface mapping | Basic detection of soil types
- Biomass mapping | Water stress
- Thermal heat mapping | Plant species identification 
## Band characteristics
Sensor	 Start WL(nm)  Stop WL (nm)	CWL (nm)	FWHM (nm)	Color
S1	433	453	443	20	VIOLET
S2	457.5	522.5	490	65	BLUE
S3	542.5	577.5	560	35	GREEN
S4	650	680	665	30	RED
S5	697.5	712.5	705	15	RED EDGE 1
S6	732.5	747.5	740	15	RED EDGE 2
S7	773	793	783	20	NIR 1
S8	784.5	899.5	842	115	NIR 2
S9	855	875	865	20	NIR 3

{% include  gallery id = "gallery3"%} **SAL Eng spectral resposne image**

## Optics
HFOV 35° (Horizontal Field of View)
VFOV 26° (Vertical Field of View)
DFOV 43° (Diagonal Field Of View)

Nominal Focal Length: 7.5mm

Aperture: f 2.8

## Ground sampling distances **LINK to explanation of GSDs**
The following data shows the maximum speed achievable to avoid motion blur, what your Ground Sampling Distance (GSD) will be, and your Field of View for select heights above ground level.

AGL(m)	GSD(mm/pixel)	FOV(m2)	Max UAV speed with 10 ms exposure time (m/s) - (km/h)	Max UAV speed with 1 ms exposure time (m/s) - (km/h)
50	23	30 x 23	2.3 - 8.4	23 - 84
75	35	45 x 34	3.5 - 12.7	35 - 127
100	47	60 x 45	4.7 - 16.9	47 - 169
150	70	90 x 68	7.0 - 25.3	70 - 253
200	94	120 x 90	9.4 - 33.8	94 - 338
300	141	180 x 135	14.1 - 50.6	141 - 506
400	188	240 x 180	18.8 - 67.5	188 - 675

## UAV Systems for our Maia imagers
The MicaSense unit and DLS will be supplied fully integrated with a UAV system. This will ensure that each image is accurately time and geostamped for prostprocessing.

These will be supplied with either:

###DJI M100
System information -DJI Website

###DJI M210
System information -DJI Website


## Units **Need this for non long-term loan instruments?**

 Model and Serial Number | Availability | Calibration Status and Documents | Location and NASA AERONET Page 
 --------------------------------| :----------: | -------------------------------- | ------------------------------ 
 Cimel 318-2-T #366              |   🟥        | Undergoing repair and calibration | N/A, [#366](https://aeronet.gsfc.nasa.gov/cgi-bin/data_display_aod_v3?site=Loch_Leven&nachal=2&level=1&place_code=10)
 Cimel 318N-EBS9 #655            |   🟨        | Final calibration checks          | N/A, [#655](https://aeronet.gsfc.nasa.gov/cgi-bin/data_display_aod_v3?site=Edinburgh&nachal=2&level=1&place_code=10) 
