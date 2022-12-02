---
title: Maia- Worldview (WV) Multispectral Imager
layout: single
permalink: /instruments/atmospheric_equipment/SAL_Maia_WV
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
The Maia WV is a UAV mounted multispectral camera with the same wavelength intervals as DigitalGlobe WorldView-2 satellite.

MAIA WV is based on an array of 9 sensors (1 RGB and 8 monochrome with relative band-pass filters) to detect multispectral imagery in the VIS-NIR spectrum from 390 nm to 950 nm.

{% include  gallery id = "gallery1"%}
{% include  gallery id = "gallery2"%}

## Where would you use this sensor? **Informal or 'Example applications'**
- Precision agriculture | Vegetation health
- Geological surface mapping | Basic detection of soil types
- Biomass mapping | Water stress
- Coastal and Oceanographic through 
- Thermal heat mapping | Plant species identification
 
## Band characteristics
Sensor	Start WL(nm)	Stop WL (nm)	CWL (nm)	FWHM (nm)	Color
S1	395	450	422.5	55	VIOLET
S2	455	520	487.5	65	BLUE
S3	525	575	550	50	GREEN
S4	580	625	602.5	45	ORANGE
S5	630	690	660	60	RED
S6	705	745	725	40	RED EDGE
S7	750	820	785	70	NIR 1
S8	825	950	887.5	125	NIR 2
S9	-	-	-	-	RGB

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
