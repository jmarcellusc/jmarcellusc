<p align="left"> <img src="https://komarev.com/ghpvc/?username=jmarcellusc&label=Profile%20views&color=0e75b6&style=flat" alt="jmarcellusc" /> </p>

<h1 align="center">Juan Marcel Campos</h1>
<h4 align="center"> ⇨ Geosciences, Cartography, Remote Sensing, Statistics, and Data Analyst</h4>
<h6 align="right">Page Updated on November, 2025</h6>

---
## About Me
A Geospatial and Data Analytics Researcher focused on driving scientific progress in geologic, environmental, and statistical domains. This researcher specializes in developing and optimizing efficient data pipelines, having significantly streamlined numerous processing methods, toolkits, and scientific scripts since 2023 to enhance overall data efficiency. This individual is a student at the University of Texas at San Antonio (UTSA), holding a prior Graduate Certificate in GIS. Outside of academic pursuits, they are an amateur photographer, showcasing work at [jmarcelphotography.com](https://www.jmarcelphotography.com/).  

## Work Synopsis and Table of Contents
Driving software development and data efficiency by enhancing and updating existing codes and toolkits across platforms, including ESRI (GIS), native Python, and VBA (Excel/Access). This optimization improves functionality, streamlines workflows for geologic mapping and remote sensing projects, and incorporates advanced techniques like machine learning while ensuring compatibility with the latest industry standards

### Ongoing Projects
- **UPDATED: Imagery Sensing Toolkit** (see information at the "Machine Learning Applications", Adding more functions) - [Version v1.1](#machine-learning-applications)
- **Earth Systems Geologic Mapping Project** - REQUIRED: Refining Datasource and Citation Database: [New Geological Mapping Project](#geologic-mapping)
- **Ontological Database** - REQUIRED: Batch importation and External database connection (GIS):  [Ontolgical Database Schema Project](#ontological-database)
- **Data Extraction Toolkits** - RECENT: Updated A.I. Prompt Toolkit: [Data Extraction Toolkits](#data-extraction)
- **Lidar Toolkit** - PAUSED: Full Functional Toolkit (will add recipes for batch processsing): [Lidar Toolkits](#lidar-toolkit)
- **Metadata Applications** - PAUSED: Various Applications Available (Update Plans): [Metadata Applications](#metadata-applications)
- **Hydrological Toolkits** - PAUSED: Writing literature and documentation. [Data Extraction Toolkits](#hydrological-tools)
- **Web Applications** - Collections of Google Earth Engine Toolkits [Web Applications](#web-applications)

* **TEMPORARY:** Presenting Drones: "Drone Example: Pico De Orizaba" -  **Link** (Copy and Paste Manually): https://experience.arcgis.com/experience/f1fb7db94c51450c9cc7799ab744d9b2/

### Planned Project and Tasks
  - **Attribution** (Database) Toolkits
  - **Microsoft Access** Datasource and Citation Database
  - **ESRI Cartography** Toolkit Updates
    - **Geology (GeMS) Validation**
      - Geologic Unit Assembler
      - Table Connection Verification
      - Geologic Plate Creator and Validator
    - **Quality Control and Assessment**
      - Vector Line-work
      - Polygon Area-work
  - **Database** Toolkits
    - Datasource and Citation Database
    - LIGARE Geologic Unique Coding
  - **Excel** Toolkits
  - **Google Earth Engine**
    - Landslide Analysis
    - Burn Region Analysis
    - Land Footprint Analysis
      - *and many other toolkits*


## Ontological Database
I'm creating an ontological database that includes terms translations for the purpose of robust sematic interoperabilitiy and the ability for linguistic cross boundary transferability. The ontological structure will provide necessary formal adn explicit framework to define concepts of multi-definitions By hosting translations directly within this defined schema, your database ensures that every system, analyst, or application accessing the data—regardless of their operational language—refers to the exact same concept (e.g., the English term "invoice" maps to the defined concept FinancialDocument, which then translates directly and unambiguously to its French, German, and Spanish counterparts). This unified approach guarantees data consistency and accurate cross-lingual knowledge sharing, transforming disparate terms into a single, cohesive, and semantically rich knowledge graph.

* **Ontological Database** - **IMPROVED:** Improved database structure and introduced translation schema (including additional fixes and enhancements).
  - Creation of administration and schema database using python coded menu system. This will import all important sources and required citation, copyrights, usage, and terms from sources. Database, while geological will target translations of various types.

   <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Ontological_Database.png" alt="Ontological Administration" width="40%">
* **Local Datasource/Citation Database** - I created a local datasource and citation database to establish a reliable, personalized repository for managing, citing, and organizing information relevant to my specific projects or domain.
  *  **Phase 1** - Inital Creation - Completed
  *  **Phase 2** - Verification and Improvements;
      -  **In-Progress** Verify batch information extraction using the AI Prompt Management and Methodology.
  *  **Phase 3** - **Pending**, Incorporation into or Methods of Data Transfer to Ontological Database
 
#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Geologic Mapping
Implementing a [New Geologic Mapping](https://github.com/jmarcellusc/Earth-Systems-Geologic-Map-Project/) scheme that incorporates modern standards to better reflect utility infrastructure changes, moving beyond outdated conventional mapping practices. I'll be starting to create digital geological map, including interactive websites and products. The current process is the creation of surface models; 2 of material impervious type (canopy and ground); 2 of elevation type (hillshade and elevation contour). These are fundamental models that will overlay geologic information. I'll be starting with geologic maps in the State of Texas.
* **Phase 1** - [Impervious "Permeability" Canopy Model](https://ee-marcelluscampes.projects.earthengine.app/view/hydroimpervious-canopy-surface) - **"Model Created",** this preliminary model data that is the basis for the Hydrologic Impervious Ground Model (currently in progress) and serves in illustrating regions where geologic area is covered by anthropogenic (man-made) materials or natural vegetation canopy.
* **Phase 2** -  [Impervious "Permeability" Ground Model](https://ee-marcelluscampes.projects.earthengine.app/view/hydroimpervious-canopy-surface) - **"Model Created",** this is presented with Phase 1, Canopy-Model. Both the canopy and ground models will be added to a geologic map as an overlay, highlighting anthropogenic (man-made) ground, vegetation canopy only, and water. 
  * Updated: [Overturn Maps Tools](https://www.dropbox.com/scl/fi/mvjrtkn8zqkrv2iwz6ou3/Overture-Maps-Downloader-v1b.zip?rlkey=q9mdeu0skhzc76kjwmys2q66s&st=7tsj5me4&dl=0)
  * Updated: [Map Neatline Tool v3.1](https://www.dropbox.com/scl/fi/tflazuzs75u2nah0zo60c/Map-Neatline-Tool-Public.zip?rlkey=fbbbf66shwcul36ent0o0329u&st=9rs3c1tc&dl=0)
* **Phase 3** - USGS Elevation Data Hillshade - **"In-Progress"** - Will explore USGS and ESA products.
* **Phase 4** - USGS Elevation Data Contours
* **Phase 5** - Project Structure & Administration Creation - **"In-Progress";** Includes generation of neatlines, GeMS project creation, and database schema. The project region is the State of Texas and Mexico (northern) geology.

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Lidar Toolkit
  - LiDAR Toolkit Processer (Multicore Thread Processing)
    - Current Batch Tools:
      - Conversion: LAZ to LAS
      - Filter by Classification
      - Filter: Extended Local Minimum
      - Filter: Outlier: Radial or Statistical
      - Filter: Simple Morphological
      - Filter: Ground Filter Generalized
    - Conversion: LAS to Tiff
      - Additional Tools and Filters will be added. Give Credit to [PDAL](https://pdal.io/en/2.8.4/)
  - LiDAR Secondary Toolkit (Mutlicore Thread Processing)
    - Current Batch Tools:
      - Process: Equal Area Segmentation
      - Filter: Elevation Outlier by Threshold
      - Filter: Smooth LAS
      - Will depreciated and move functionalites to LiDAR Toolkit Processor

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Classification Toolkits
 * **NEW:** SMILE Google Earth Engine Random Forest
   * **METHOD:**  Introduction of AplhaEarth's Google Deep AI Imagery
   * **METHOD:**  Efficient approach in processing random forest of 3 moasic image periods, multistack
     * Example: GEE SMILE Random Forest classification, similar NLCD classification. 
[![GEE Random Forest Classifier Example](https://imgur.com/jq49KYW.png)](https://youtu.be/KmfPY4PzZ20)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Data Extraction
 * **NEW:** [AI Prompt Management Program - v2.3](https://www.dropbox.com/scl/fi/6dyipnkja1nfrwjtd1d5h/AI-Prompt-Management-v1d.zip?rlkey=6k8uhbrusqe69syhjxai6asiv&st=by69jip6&dl=0) - Update: Dec, 15 2025. Fixed: Previous version was not saving on import. Dynamic fields option that opens the possibility to save a custom prompt to the local database. Also features; ability to share a database, import a database, appends a user system name, and menu system improvements.
 * **Download 'Overture Maps' Data** 
- [Download Tool](https://www.dropbox.com/scl/fi/mvjrtkn8zqkrv2iwz6ou3/Overture-Maps-Downloader-v1b.zip?rlkey=q9mdeu0skhzc76kjwmys2q66s&st=9egi4rw7&dl=0) (Update: v1b) - See: [Read Me Information](https://github.com/jmarcellusc/Download-Overture-Maps-Data)
  - **NOTES:** Only works with release: 24 September 2025	[2025-09-24.0	v1.12.0], schema v1.12.0. Please enter "2025-09-24.0" as the date version. Since Overturn Maps is currently updating their data scheme and storage repositories, I'll wait after 2025 to create an new update. Even so, you are open on aquiring thier complete dataset from: [Overturn Maps](https://overturemaps.org/)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Hydrological Tools
 - Depression Identification and Depression Region Enclosure Fill - Completed, working on literature to document a possible new method
 - General hydrological tools are on paused.

#### [Return to Synopsis Introduction](#work-synopsis-table-of-contents)
---


## Machine Learning Applications
#### Imagery Sensing Toolkit 
**Version v1.1**; - I would like to extend special gratitude to Jeff Jenness. His invaluable toolkit and documentation have been foundational to my understanding of elevation surfaces over the years. With addition to more hillshade and curvature toolkits, I will be incorporating more of Florinsky methodologys on surfaces as his literature are highly regarded. Not yet available for download.
Adds the following:
  - Spatial Differencing
  - Laplacian Differencing
  - Independent Component Analysis (ICA)
  - Principal Component Analysis (PCA)
  - Uniform Manifold Approximation and Projection
  - DEM Kits: Analysis Surface Metrics
    - Slope: [4-Cell, N-S Gradients, (4,8,Weighted) Gradients]
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Imagery%20Sensing%20Toolkit.png" alt="Sample 1" width="50%">

**Version v1.0** - Inital creation, functions 1-14. [Imagery Sensing Toolkit](https://www.dropbox.com/scl/fi/7srzeplaej1qsm67xzstx/Imagery-Preprocess-Toolkit-v1.zip?rlkey=crxjl4elktjqp888eqw82qwx7&st=9pltftxw&dl=0)
 - Read Raster Info
 - Filter Out Dimensions
 - Creation of Binary Mask
 - Segmentation by Dimension (&Directory)
 - Reorganize Imagery Bands (&Directory)
 - Split Imagery into Grids (&Directory)
 - Normalize Imagery (&Directory)
 - Standardized Imagery (&Directory)
 - Detrend Imagery (&Directory)
<br>


#### Machine Learning Toolkit
##### 1. Automative Segmentation Tool
 - Complete Toolkit (train/inference)
 - Adjustable Parameters: {currently improveing}
 - Export/Import Model Files
 - Export/Import Data Files
   - **UPDATING:** Currently in Improving Automation, Switching Parameters, and More
   - Screenshot Test:
    - <img src="https://imgur.com/gtw0jfT.png" alt="Sample 1" width="50%">
    - <img src="https://imgur.com/k3Va2l2.png" alt="Sample 2" width="50%">
   
<br>

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Web Applications
#### Google Earth Engine
  - **New:**  [Foliage Phenology Exploration Toolkit v1.1](https://ee-marcelluscampes.projects.earthengine.app/view/foliage-phenology-inspection-tool) - Recently created and updated that aids in determination of foliage seasonal phenology.
    - Web application is very new and is currently active for canopy (pending low surface vegetations).
  - **Updated:** [Wetlands Exploration Toolkit v3.0](https://ee-marcelluscampes.projects.earthengine.app/view/wetlands-exploration-toolkit-v11) - Recently updated.
    - Added 2024, 2025 Years.
    - Added SAR Surface Water Detection.
    - Added New Chlorophyll Detection (Alpha Testing)
  - 
  - [Soils Expliratory Tool v1.1b](https://ee-marcelluscampes.projects.earthengine.app/view/soils-exploratory-tool-in-progress-v11b) - [Processing Refinements]
  - [Topographic Terrain Tool v1](https://ee-marcelluscampes.projects.earthengine.app/view/topographic-inspector) - [User Refinements]
  - [Political Boundary v1](https://ee-marcelluscampes.projects.earthengine.app/view/political-country-selection) - [Processing Refinements]
  - [Aerosols Exaiminer Tool v1](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-sensing-tool-v10d) - [Issues documented, requires recoding.]
#### ESRI 
  - World Minerals Dashboard- [**! Removed**, Moving project to Google Earth Engine as data hosting with ESRI is costly.]

<br>

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Metadata Applications
 - XML Editor Conversion
   - **COMPLETED:** Pending Link
    - Runs xml extraction into Excel Macro database. Eases in xml replication, modification, and editing, particular to ESRI metadata.
    - Current Batch Tools:
      - Extract Metadata (xml >> excel)
      - Update Metadata (xml >> excel >> xml)
      - Create Metadata (excel >> xml)
  - PDF Metadata Updater:
    - **COMPLETED:** [PDF Metadata Updater](https://github.com/jmarcellusc/PDF-Metadata-Updater)
    - Reads Excel Macro database (inventory of pdf metadata) and appends metadata to PDF with advance customizability.
    - Currently single file selection with selectable metadata record injection.
    -   - Python Small GIS Projects:
  - **COMPLETED:** [CMYK Palette Generator](https://github.com/jmarcellusc/CMYK-Palette-Generator)


#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Documentation Processing Applications
#### Documents and Images
  - [PDF Toolkit v1b](https://www.dropbox.com/scl/fi/kdvribiwzg1kmj6amwh6r/PDF-Toolkit-v1b.zip?rlkey=p1gjp84z4byf520ozj6ceii6m&st=kye2vhns&dl=0) - [Requires [Excel Metadata Database/Form](https://www.dropbox.com/scl/fi/8ucgwe12epf82hv99cjpc/PDF_MetadataDB.zip?rlkey=6ybfdbmpa9md1xoxyqazq47bd&st=gm6o3f5v&dl=0)]
  - [CMYK Palette Generator](https://www.dropbox.com/scl/fi/2t54rddhgh0hmcnabre4g/CMYK-Color-Palette-Generator.zip?rlkey=mhjynsesdyvvawl4c0w1gb478&st=w4is55to&dl=0) - [Additional Tools Planned]

#### Data
  - Download Toolkit v1c - Powerful and moving into a private collection.
  - [XML Toolkit v1b](https://www.dropbox.com/scl/fi/4nduxh4hhux7rvugnf920/XML-Toolkit-v1b.zip?rlkey=5k36dvn4skjbdha7wuifax6eb&st=91mwivf3&dl=0) - Working, will update soon. [Minor Issues]
  - [SAS Converter](https://www.dropbox.com/scl/fi/vppja9koesu2rxiaibr6d/SAS-Converter-v1b.zip?rlkey=haqvy27qxvobalris3ovlcv3n&st=xy1v027i&dl=0) - Respectful source credit:  Jared Hobbs [sas7bdat](https://bitbucket.org/jaredhobbs/sas7bdat/src/master/)
  - [VBA Excel Collection Scripts](https://github.com/jmarcellusc/VBA-Excel)

<br>

## Geospatial
#### Cartographic
  - Geologic Unit Color Toolkit: [Excel Worksheet](https://www.dropbox.com/scl/fi/slafgkzxl642iut2wqiy0/GeMS-FGDC-USGS_Geologic-Unit-Color-Toolkit.zip?rlkey=ob9pifm19s66l1suq8lrhogcd&st=mmem5azq&dl=0) - GeMS, FGDC, & USGS Compliant
  - Map Neatline Tool: [Updated v3.1](https://www.dropbox.com/scl/fi/tflazuzs75u2nah0zo60c/Map-Neatline-Tool-Public.zip?rlkey=fbbbf66shwcul36ent0o0329u&st=nfos1ys2&dl=0) - Fixed path issues and process cleanup.

<br>

## Notes
#### Chemical
 - [Elements - Notes](https://github.com/jmarcellusc/Elements-Notes-) - A compilation of notes for chemical elements, on-going.

<br>
<br>

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Timeline
### **Mid 2025**
  - **NEW** Machine Learning Imagery (Preproces Toolkit, ML Tool)
  - **NEW** Map Neatline Creator: Updated to v3.0
  - **NEW**  CMYK Palette Generator: Revising Code, conversion to executable
  - **NEW:**  XML ESRI Metadata Toolkit:  Revising Code
  - **NEW** GeMS FGDC USGS Geologic Unit Color Toolkit [Excel Worksheet]
  - **NEW:** PDF Toolkit v1b: [Download] - Requires [Excel Metadata Database/Form]
  - **NEW:** Download Toolkit v1c
  - **PLANNED**
    - Random Forest Land Classification Tool
    - Hydrological Tools 
    - Imagery Preprocess Toolkit v1
    - Lidar Toolkit - various functionalites 
    - Wold Minerals Dashboard (ESRI Hosting Cost is expensive, Will be migrating to Square Space)
    - Reverse Geocode - Conversion to ESRI Geoprocessing
    - Update Google Earth Engine Current Applications - (Update additional timeframe)
    - GeMS Additional Mapping Toolkits
    - OCR Functionalies and Extractions
   
<br>



### REMOVING SECTION: **Early 2025**
   - In Progress: ESRI Interactive Web Applications:
    - PDF Metadata Toolkit - Requires Minor Conversion
    - XML Metadata Toolkit - Requires conversion to ESRI Geoprocessing Kit (current Stand Alone) 
    - [Houston-Galveston Area Council Hurricane Evacuation Dashboard](https://experience.arcgis.com/experience/d24314506471423f98b5252a1b7f5f0f)
  - XML Editor Conversion
    - Runs xml extraction into Excel Macro database. Eases in xml replication, modification, and editing, particular to ESRI metadata.
    - Current Batch Tools:
      - Extract Metadata (xml >> excel)
      - Update Metadata (xml >> excel >> xml)
      - Create Metadata (excel >> xml)
  - PDF Metadata Updater:
    - Reads Excel Macro database (inventory of pdf metadata) and appends metadata to PDF with advance customizability.
    - Currently single file selection with selectable metadata record injection.
  - Additional Single Functionlities Toolkits
    - SAS Conversion
    - Graphic Design CMYK Template Generator
- **Planned**
  - (**UPDATE:** Will incorporate into LiDAR Toolkit Procssor) ESRI LiDAR (Las) Collection of Tools (Active: LiDAR Python Class/Tools)
    - Reclassification with Parallel Processing
    - Sink Detection
    - Interpolation
  - (**Paused:**) Google Earth Engine - Landslides Exploratory Tool v1.0a - **Initiated** Not posted and delayed due to other higher priority projects.
  - ***Fix Errors: Google Earth Engine - Soils App: {Incorrect Bin Statement, Append Slope, Menu-Fixes}***
  - Google Earth Engine - Wetlands Exploratory Tool v1.0d - **To Append:** Generalization, Chart Production
  - Google Earth Engine - Soils Exploratory Tool v1.1b - **To Append:** Issues: Reset for Binning, Data Boundaries (Outside Edge Notice), Color Palette Processing Time, Increase Step Size for Extensive Range Elevation. Introduce Slope and Aspect

<br>

- **Active**
  - LiDAR Python Class/Tool ~ **[COMPLETED] Upgraded Additional Filters**
  - Google Earth Engine - Soils App ~ **[PAUSED] Downgraded to Low Priorty**
  - Python Small GIS Projects:
    - **COMPLETED:** [CMYK Palette Generator](https://github.com/jmarcellusc/CMYK-Palette-Generator)
    - **COMPLETED:** [PDF Metadata Updater](https://github.com/jmarcellusc/PDF-Metadata-Updater)
    - **COMPLETED:** [ReverseGeocode](https://github.com/jmarcellusc/ReverseGeocode)
    - **DELAYED**: ESRI Shapefile Integrity (QA for Shapefiles)
    - **UPDATING:** ChatGPT Query (produces Markdown pages)
  - Vector Line Quality Control ESRI Tool
  - Geological Unit Code Tool - ESRI Tool
  - Google Earth Engine: Wetland Evaulation App
  - ESRI Global ID Tool (various process ESRI Tool)
  - Releasing Google Earth Engine-Apps Fixes; Verions 1.0c
    - Known Issues {Incorrect Footer Date, MinMax issues with Sentinel 5}

- **Completed**
  - PDF Metadata Updater - [Link](https://github.com/jmarcellusc/PDF-Metadata-Updater)
  - CMYK Palette Generator - [Link](https://github.com/jmarcellusc/CMYK-Palette-Generator)
  - ReverseGeocode - [Link](https://github.com/jmarcellusc/ReverseGeocode)
  - **Google Earth Engine** - [Soils Exploratory Tool v1.1b](https://ee-marcelluscampes.projects.earthengine.app/view/soils-exploratory-tool-in-progress-v11b)
  - **Google Earth Engine** - [Wetland Exploratory Tool v1.0c](https://ee-marcelluscampes.projects.earthengine.app/view/wetlands-exploratory-tool-in-progress-v10c)
  - **Google Earth Engine** - [Aerosols Examiner App](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-sensing-tool-v10d)
  - NEW: https://github.com/jmarcellusc/ArcGIS-Pro_Digitization_Tools - (Beta; pending real-time review)
  - **Text Correction Tool** Version 3.0
  - **Class Inspector** Version 2.0

- **Archive**
  - Graphic Design Scheme Generator: "Graphic Design Scheme"
  - *Testing Version:* [Google Earth Engine-Apps](https://github.com/jmarcellusc/Google-Earth-Engine/tree/main)
  - **Trace Elements of Soils: Notes Chapter 1 & 2**
  - **Database Spell Checker**
  - **Color Extraction** (from image) - uses KMeans to extract colors and creates a PDF report. Will be native and embedded into other scripts and toolkits.
    - STATUS: Stand-Alone complete. Conversion into ESRI toolscript is paused for a python library issue.
    - STATUS: Will expand tool to run multi-sampling and multi-threshold. Method requires targeted improvement.
  - **PDF Text/Latex** (with Python) - using templates to create variable design PDF documents. Will be native and embedded into other scripts and toolkits.

---

<h2 align="center">About Me</h2>
Research in Geological Sciences (Petrology, Geochemistry, Geomorphology, Sedimentation), GIS (Geostatistics, Cartography, Geospatial Data Science, Remote Sensing), Attributional Data Science (Python, VBA, JavaScript)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Contact Information

- Email: **marcelluscampes@gmail.com**
- Website: **https://www.jmarcelphotography.com/**
