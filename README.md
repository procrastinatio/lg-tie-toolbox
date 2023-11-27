# TIE #

Python module for "Trace Information Extraction" (TIE) method

## Install ##

### Requirements ###

* PyQt or WxPython

PyQt/PySide or wxPython
        installed.



SwissAlti  Format

    gdalinfo swiss_1226_4.tif
    Driver: GTiff/GeoTIFF
    Files: swiss_1226_4.tif
    Size is 4375, 3000
    Coordinate System is:
    PROJCRS["CH1903+ / LV95",
        BASEGEOGCRS["CH1903+",
            DATUM["CH1903+",
                ELLIPSOID["Bessel 1841",6377397.155,299.1528128,
                    LENGTHUNIT["metre",1]]],
            PRIMEM["Greenwich",0,
                ANGLEUNIT["degree",0.0174532925199433]],
            ID["EPSG",4150]],
        CONVERSION["Swiss Oblique Mercator 1995",
            METHOD["Hotine Oblique Mercator (variant B)",
                ID["EPSG",9815]],
            PARAMETER["Latitude of projection centre",46.9524055555556,
                ANGLEUNIT["degree",0.0174532925199433],
                ID["EPSG",8811]],
            PARAMETER["Longitude of projection centre",7.43958333333333,
                ANGLEUNIT["degree",0.0174532925199433],
                ID["EPSG",8812]],
            PARAMETER["Azimuth of initial line",90,
                ANGLEUNIT["degree",0.0174532925199433],
                ID["EPSG",8813]],
            PARAMETER["Angle from Rectified to Skew Grid",90,
                ANGLEUNIT["degree",0.0174532925199433],
                ID["EPSG",8814]],
            PARAMETER["Scale factor on initial line",1,
                SCALEUNIT["unity",1],
                ID["EPSG",8815]],
            PARAMETER["Easting at projection centre",2600000,
                LENGTHUNIT["metre",1],
                ID["EPSG",8816]],
            PARAMETER["Northing at projection centre",1200000,
                LENGTHUNIT["metre",1],
                ID["EPSG",8817]]],
        CS[Cartesian,2],
            AXIS["(E)",east,
                ORDER[1],
                LENGTHUNIT["metre",1]],
            AXIS["(N)",north,
                ORDER[2],
                LENGTHUNIT["metre",1]],
        USAGE[
            SCOPE["Cadastre, engineering survey, topographic mapping (large and medium scale)."],
            AREA["Liechtenstein; Switzerland."],
            BBOX[45.82,5.96,47.81,10.49]],
        ID["EPSG",2056]]
    Data axis to CRS axis mapping: 1,2
    Origin = (2593750.000000000000000,1164000.000000000000000)
    Pixel Size = (2.000000000000000,-2.000000000000000)
    Metadata:
      AREA_OR_POINT=Area
    Image Structure Metadata:
      INTERLEAVE=BAND
    Corner Coordinates:
    Upper Left  ( 2593750.000, 1164000.000) (  7d21'28.66"E, 46d37'42.61"N)
    Lower Left  ( 2593750.000, 1158000.000) (  7d21'28.96"E, 46d34'28.29"N)
    Upper Right ( 2602500.000, 1164000.000) (  7d28'20.03"E, 46d37'42.70"N)
    Lower Right ( 2602500.000, 1158000.000) (  7d28'19.92"E, 46d34'28.38"N)
    Center      ( 2598125.000, 1161000.000) (  7d24'54.39"E, 46d36' 5.55"N)
    Band 1 Block=4375x1 Type=Float32, ColorInterp=Gray
      NoData Value=-9999
      
      
      
      tiffinfo  swiss_1226_4.tif
    TIFFReadDirectory: Warning, Unknown field with tag 33550 (0x830e) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 33922 (0x8482) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34735 (0x87af) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34736 (0x87b0) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34737 (0x87b1) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 42113 (0xa481) encountered.
    TIFF Directory at offset 0x8 (8)
      Image Width: 4375 Image Length: 3000
      Bits/Sample: 32
      Sample Format: IEEE floating point
      Compression Scheme: None
      Photometric Interpretation: min-is-black
      Samples/Pixel: 1
      Rows/Strip: 1
      Planar Configuration: single image plane
      Tag 33550: 2.000000,2.000000,0.000000
      Tag 33922: 0.000000,0.000000,0.000000,2593750.000000,1164000.000000,0.000000
      Tag 34735: 1,1,0,8,1024,0,1,1,1025,0,1,1,1026,34737,15,0,2049,34737,8,15,2054,0,1,9102,2062,34736,3,0,3072,0,1,2056,3076,0,1,9001
      Tag 34736: 674.374000,15.056000,405.346000
      Tag 34737: CH1903+ / LV95|CH1903+|
      Tag 42113: -9999
    
    
