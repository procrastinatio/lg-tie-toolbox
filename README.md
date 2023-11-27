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
    
 From ESRI


    gdalinfo  toto.tif
    Driver: GTiff/GeoTIFF
    Files: toto.tif
           toto.tif.ovr
           toto.tif.aux.xml
    Size is 400, 400
    Coordinate System is:
    PROJCRS["CH1903+_LV95",
        BASEGEOGCRS["CH1903+",
            DATUM["CH1903+",
                ELLIPSOID["Bessel 1841",6377397.155,299.152812800003,
                    LENGTHUNIT["metre",1]]],
            PRIMEM["Greenwich",0,
                ANGLEUNIT["degree",0.0174532925199433]],
            ID["EPSG",4150]],
        CONVERSION["Hotine Oblique Mercator (variant B)",
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
            AXIS["easting",east,
                ORDER[1],
                LENGTHUNIT["metre",1]],
            AXIS["northing",north,
                ORDER[2],
                LENGTHUNIT["metre",1]],
        ID["EPSG",2056]]
    Data axis to CRS axis mapping: 1,2
    Origin = (2600000.000000000000000,1200200.000000000000000)
    Pixel Size = (0.500000000000000,-0.500000000000000)
    Metadata:
      AREA_OR_POINT=Area
      DataType=Elevation
    Image Structure Metadata:
      COMPRESSION=LZW
      INTERLEAVE=BAND
    Corner Coordinates:
    Upper Left  ( 2600000.000, 1200200.000) (  7d26'22.50"E, 46d57'15.14"N)
    Lower Left  ( 2600000.000, 1200000.000) (  7d26'22.50"E, 46d57' 8.66"N)
    Upper Right ( 2600200.000, 1200200.000) (  7d26'31.96"E, 46d57'15.14"N)
    Lower Right ( 2600200.000, 1200000.000) (  7d26'31.96"E, 46d57' 8.66"N)
    Center      ( 2600100.000, 1200100.000) (  7d26'27.23"E, 46d57'11.90"N)
    Band 1 Block=128x128 Type=Float32, ColorInterp=Gray
      Min=533.536 Max=560.584 
      Minimum=533.536, Maximum=560.584, Mean=542.713, StdDev=8.284
      NoData Value=-9999
      Overviews: 200x200
      Metadata:
        RepresentationType=ATHEMATIC
        STATISTICS_COVARIANCES=68.61793564477497
        STATISTICS_MAXIMUM=560.58416748047
        STATISTICS_MEAN=542.71312800255
        STATISTICS_MINIMUM=533.53594970703
        STATISTICS_SKIPFACTORX=1
        STATISTICS_SKIPFACTORY=1
        STATISTICS_STDDEV=8.2835943674697
 

    tiffinfo toto.tif
    TIFFReadDirectory: Warning, Unknown field with tag 33550 (0x830e) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 33922 (0x8482) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34735 (0x87af) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34736 (0x87b0) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 34737 (0x87b1) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 42112 (0xa480) encountered.
    TIFFReadDirectory: Warning, Unknown field with tag 42113 (0xa481) encountered.
    TIFF Directory at offset 0x477136 (747d0)
      Image Width: 400 Image Length: 400
      Tile Width: 128 Tile Length: 128
      Bits/Sample: 32
      Sample Format: IEEE floating point
      Compression Scheme: LZW
      Photometric Interpretation: min-is-black
      Samples/Pixel: 1
      Planar Configuration: single image plane
      Tag 33550: 0.500000,0.500000,0.000000
      Tag 33922: 0.000000,0.000000,0.000000,2600000.000000,1200200.000000,0.000000
      Tag 34735: 1,1,0,16,1024,0,1,1,1025,0,1,1,1026,34737,24,0,2048,0,1,4150,2049,34737,85,24,2050,0,1,6150,2051,0,1,8901,2054,0,1,9102,2055,34736,1,0,2056,0,1,7004,2057,34736,1,1,2059,34736,1,2,2061,34736,1,3,3072,0,1,2056,3073,34737,490,109,3076,0,1,9001
      Tag 34736: 0.017453,6377397.155000,299.152813,0.000000
      Tag 34737: PCS Name = CH1903+_LV95|GCS Name = GCS_CH1903+|Datum = D_CH1903+|Ellipsoid = Bessel_1841|Primem = Greenwich||ESRI PE String = PROJCS["CH1903+_LV95",GEOGCS["GCS_CH1903+",DATUM["D_CH1903+",SPHEROID["Bessel_1841",6377397.155,299.1528128]],PRIMEM["Greenwich",0.0],UNIT["Degree",0.0174532925199433]],PROJECTION["Hotine_Oblique_Mercator_Azimuth_Center"],PARAMETER["False_Easting",2600000.0],PARAMETER["False_Northing",1200000.0],PARAMETER["Scale_Factor",1.0],PARAMETER["Azimuth",90.0],PARAMETER["Longitude_Of_Center",7.439583333333333],PARAMETER["Latitude_Of_Center",46.95240555555556],UNIT["Meter",1.0]]|
      Tag 42112: <GDALMetadata>
      <Item name="DataType">Elevation</Item>
      <Item name="PyramidResamplingType" domain="Esri">NEAREST</Item>
      <Item name="RepresentationType" sample="0">ATHEMATIC</Item>
      <Item name="STATISTICS_COVARIANCES" sample="0">68.61793564477497</Item>
      <Item name="STATISTICS_MAXIMUM" sample="0">560.58416748047</Item>
      <Item name="STATISTICS_MEAN" sample="0">542.71312800255</Item>
      <Item name="STATISTICS_MINIMUM" sample="0">533.53594970703</Item>
      <Item name="STATISTICS_SKIPFACTORX" sample="0">1</Item>
      <Item name="STATISTICS_SKIPFACTORY" sample="0">1</Item>
      <Item name="STATISTICS_STDDEV" sample="0">8.2835943674697</Item>
    </GDALMetadata>
    
      Tag 42113: -9999
      Predictor: none 1 (0x1)



clipping data
-------------


    arcpy.Clip_management(lyr,"2600000 1200000 2600200 1200200",r"h:/tmp/toto.tif", "#", -9999, "NONE", "NO_MAINTAIN_EXTENT")
