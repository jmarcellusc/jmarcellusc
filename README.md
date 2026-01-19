<p align="left"> <img src="https://komarev.com/ghpvc/?username=jmarcellusc&label=Profile%20views&color=0e75b6&style=flat" alt="jmarcellusc" /> </p>

<h1 align="center">Juan Marcel Campos</h1>
<h4 align="center"> ⇨ Geosciences, Cartography, Remote Sensing, Statistics, and Data Analyst</h4>
<h6 align="right">Page Updated on December, 2025</h6>

---
## About Me
A Geospatial and Data Analytics Researcher focused on driving scientific progress in geologic, environmental, and statistical domains. This researcher specializes in developing and optimizing efficient data pipelines, having significantly streamlined numerous processing methods, toolkits, and scientific scripts since 2023 to enhance overall data efficiency. This individual is a student at the University of Texas at San Antonio (UTSA), holding a prior Graduate Certificate in GIS. Outside of academic pursuits, they are an amateur photographer, showcasing work at [jmarcelphotography.com](https://www.jmarcelphotography.com/).  

### Disclaimer
The tools, code, and information in this repository are for **educational and research purposes only** and are not intended for commercial use or production environments. All content is provided "as-is" without warranty. Users assume full responsibility for compliance with local laws and third-party terms of service.

---

## Work Synopsis and Table of Contents
Driving software development and data efficiency by enhancing and updating existing codes and toolkits across platforms, including ESRI (GIS), native Python, and VBA (Excel/Access). This optimization improves functionality, streamlines workflows for geologic mapping and remote sensing projects, and incorporates advanced techniques like machine learning while ensuring compatibility with the latest industry standards

### <mark>Ongoing Projects</mark>
#### <ins>New</ins>
   - **Geochemical Web Apps** - Added a series of geochemistry and geology field webapps. [Link](#geologic-mapping) - [Items](https://www.jmarcelphotography.com/geologygeospatial)
      - **Spectral Library Manager**  - Added to manage, extract, subset spectral libraries. Included are various analysis methods that can be archived within the library. See: [Youtube](https://youtu.be/yPki8EFPXLQ) 
      - **Geologic Mineral Logger** - Added a minerals logger which can import spectra, here injested from the USGS Spectral Library v7 (after JSON conversion). Due to the large data, the import is an indexdb in which the datafile must be always present at the same location and index is stored in the web browswer. It runs an matching algorithm to a csv imported for the sample. See here: [Link](#geologic-mapping)
     - **Soils Classification Reference** - A simple reference guide for soils identifcation with engineering aspects included. This webapp will require additional upgrades and improvements, pausing.
     - **Soil Log Classifier** - An advance web-based field logger that aids in soil sampling, includes a map, import/export options, and auto computated classifications; **Private**.
     - **Geologic Formation Log Classifier** - An advance web-based field logger that helps with nominal limestone, sandstone, mudstone formations, which includes a map, import/export options, and auto computated classifications; **Private**.
     - **Aqueous Log Classifier** - An advance web-based field logger that aids with aqueous sampling, includes a map, import/export options, and auto computated classifications; **Private**.
     - **Geologic Borehole/Core Logger** - An advance web-based field logger that aids with boring, core sampling, includes a map, import/export options, and auto computated classifications; **Private**.
     - **Geologic Traverse/Structure Logger** - An advance web-based field logger that aids with field exploration, includes a map, stereonet, import/export options, and auto computated classifications; **Private**.
     - **Geologic Sampler/Regolith Manager** - An advance web-based field logger that aids with management of samples/ includes a map, import/export options, and auto computated classifications; **Private**. 
  - **Google Geolocator** - Developed personal geocode location downloader using Google Cloud API (private). [Google Geolocator](#data-extraction)
  - **Mineral-Elements-Commodities** - Template created: [Geologic Mapping](#geologic-mapping)
  - **Historical Weather Explorer** - Developed an interactive historical weather tool that integrates Open-Meteo data with FEMA records. This initial version establishes the core architecture for data acquisition, with future iterations planned to integrate the NOAA Storm Events Database and enhance UI usability. [Link](https://www.jmarcelphotography.com/historical-weather-explorer)
  - **Numerous Web Applications** -  I've created numerous web applications, all with specific tasks in data processing, image extraction, image analysis, and started the foundation of the Geologic Mapping and Minerals Map. All these are found here: [Link](https://www.jmarcelphotography.com/geologygeospatial). Note that ~30% are not being publically shared due to their on-going improvements.
 - **Geochemical Web Apps** - Added a series of geochemistry and geology field webapps.
    - **Geochemical Explorer 1** - Simple major oxides. - [Link](https://www.jmarcelphotography.com/geochemical-explorer)
    - **Geochemical 2-3** - Major, trace, immoble-alteration, CIPW; **Private**.  - [Link](#geologic-mapping)
    - **Carbonate Aggregate Geochem** - Tailored to geochemistry of lime/dolostones, v1.1; **Private**. - [Link](#geologic-mapping)
    - **Siliciclastic Aggregate Geochem** - Created for sandstone/quartz rich aggregates; **Private**. - [Link](#geologic-mapping)
    - **Economic Aggregates Geochem** - Created for the combination of lime and silica aggregates; **Private**. - [Link](#geologic-mapping)
    - **Igneous/Volcanics Aggregates Geochem** - Created for the combination of volcanic and igneous aggregates; **Private**. - [Link](#geologic-mapping)
    - **Clay/Shale/Fines reactivity Geochem** - Created for the combination of shales/clays/fines aggregates; **Private**. - [Link](#geologic-mapping)
    - **Sulfides/Sulfates DCR Geochem** - Created for the range of elemental sulfur geochemical exploration; **Private**. - [Link](#geologic-mapping)
    - **FGDC Geologic Symbol Reference** - Fast approach on finding correct FGDC coding, under construction. [Link](https://www.jmarcelphotography.com/fgdc-geologic-symbol-reference)
    - **Geo-Coordinator Extractor** - Locate and tag extracting latitudes and longitude using Leaflet, created for Testing. Plans: Several important functionalites in aiding geographic workflows. [Link](https://www.jmarcelphotography.com/color-vision-deficiency)

#### <ins>In-Progress</ins>
  - **UPDATING- Lidar Toolkit:** Generating standard DEM production from point-cloud via pipelines:
    - DTM / Bare-earth DEM (Terrain Model) — ground-only terrain surface.
    - DSM (Digital Surface Model) — “top of everything” (canopy/roofs/bridges).
    - nDSM / CHM (Normalized DSM / Canopy Height Model) — object height above ground (DSM − DTM).
    - Hydro-flattened DEM — terrain DEM with flat, non-wavy lakes/ponds and consistent river water surfaces.
    - Hydro-enforced / Hydrologically conditioned DEM (HCD) — terrain DEM modified for correct drainage connectivity (bridge/culvert handling, burn/breach/fill as needed).
  - **Geologic Media Reference** - Geologic media reference application, created for Testing . Plans: Several including testing connections to ESRI or other hosting datasource with reference to an ontological database [Link](https://www.jmarcelphotography.com/geologic-media)
  - **ESRI Map Generic** - Map ArcGIS Java SDK connection, created for Testing. Plans: Several generic ESRI ArcGIS Online connections.
  - **Rain-Flood Simulation** - Project still requires major improvements and functionalites, the current issue is correcting any data explode, irregularities in movement, pooling, and more. The application status is working, see: [Hydrological Toolkits](#hydrological-tools)
    - Creating a long awaited rainfall/flood simulation application. Status: Completed utilizing Saint-Venant (SWE) momentum, generic parameters, 1 GB DEM limit, imagery or DEM backing, and video clip export. Version 1.0
  - **Geologic Modeling** - Creating a Alluvial Geomorphodynamics Toolkit that will explore depositions, sediment transport, and various other processes. Adding [Geologic Modeling](#geologic-modeling) 
  - **FGDC Table and Toolkit Add-In** - Adding and updating under the **Datasource Microsoft Access Database** (including forms and connections).
  - **ArcGIS Pro Feature Information Extraction** - Allows a user to read and extract information related to parsing to the Datasource Access Database or other transfers
  -  **Google Earth Engine - Elevation Product Explorer** - Required for [Geologic Mapping](#geologic-mapping) (and its products will be processed with the Imagery Sensing Toolkit to create Hillshades and others derivatives)
  -  **Datasource** Improving the Microsoft Access\Database (High Priority)
  - **LIGARE** - Geological UUID Coder/Decoder (pausing, Low Priority)
  - **A.I. Ollama Dolphin-llama3** - A.I. Development and Research. Created offline ollama LLM on external (with AnythingLLM) but will divert functionality to python programming and iterations. See: [Ollama Connect](#data-extraction)

#### <ins>Updated</ins>
  - **Advance PDF Utility** - Completed - A fully functional and essential program that executes multiple PDF-related functions, Information will be updated in a later time. [Data Extraction Toolkits](#data-extraction)
   - **Accessibility Web Apps** - Added a series of web applications, several for accessibility requirements, environmental, geological, data processing, surveys, metadata, and others.
    - **Color Palette Architect** - Visual color palette generator with various export options. - [Link](https://www.jmarcelphotography.com/color-palette-architect)
    - **Color Vision Deficiency Hub** - Targeted color CVD scoring metric - [Link](https://www.jmarcelphotography.com/color-vision-deficiency)
    - **Color Collector** - Pin-point color extraction - [Link](https://www.jmarcelphotography.com/color-collector)
    - **Color Gradient Architect** - Generates a color trajectory gradient. Plans: Expansion in color ramp production [Link](https://www.jmarcelphotography.com/color-gradient-architect)
  - **Accessibility Toolkit** - Completed; Standardizing the application suite including map contrast easurement metric. Located under the [Metadata Applications](#metadata-applications)
    - **Web App**: [Image Contrast Accessibility Check](https://www.jmarcelphotography.com/image-contrast-accessibility-check)** - Simple and alternative to the complete local program I'm developing.
    - **Web App**: [APCA (Lc Score) Check](https://www.jmarcelphotography.com/apca-lc-score)** - Allows the user to pick color values and check if it meets WCAG requirements.
  - **Advance Conda Management** - **UPDATED**, Verion 1.1 (v1a.exe) Posted here: [Link](#data-extraction)- Caution in usage, please read Disclaimer Information.
  - **LIGARE Toolkit** Older verion 1.3 is posted here: [Geometric Series](#geometric-series) but plans of improvement are in development.
  - **Imagery Sensing Toolkit** (Advance Update: Includes the remaining DEM processes and geomorphometric applications) - [Version v1.2](#machine-learning-applications)
  - **Earth Systems Geologic Mapping Project** - REQUIRED: Refining Datasource & Citation Database: [New Geological Mapping Project](#geologic-mapping)
  - **Ontological Database** - REQUIRED: Batch importation and External database connection (GIS):  [Ontolgical Database Schema Project](#ontological-database)
  - **Data Extraction Toolkits** - RECENT: Updated A.I. Prompt Toolkit: [Data Extraction Toolkits](#data-extraction)
  - **Lidar Toolkit** - PAUSED: Full Functional Toolkit (will add recipes for batch processsing): [Lidar Toolkits](#lidar-toolkit)
  - **Metadata Applications** - PAUSED: Various Applications Available (Update Plans): [Metadata Applications](#metadata-applications)
  - **Hydrological Toolkits** - PAUSED: Writing literature and documentation. [Hydrological Toolkits](#hydrological-tools)
  - **Web Applications** - Collections of Google Earth Engine Toolkits [Web Applications](#web-applications)



###  <mark>Planned Projects and Tasks</mark>
  - **Attribution** (Database) Toolkits
  - **Microsoft Access** Datasource and Citation Database
  - **ESRI Cartography** Toolkit Updates
    - **Geology (GeMS) Validation**
      - Geologic Unit Assembler
      - Table Connection Verification
      - Geologic Plate Creator and Validator
    - **Quality Control and Assessment**
      - Vector Line Quality Control ESRI Tool
      - Geological Unit Code Tool - ESRI Tool
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
* **Geologic Minerals Logger** - Logs minerals spectral and runs a match to a library database.
   * See Video here (Click on image)
   * [![Geologic Minerals Logger](https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Geologic%20Minerals%20Logger.png)](https://youtu.be/4L4YpWtK2Sw)
* **Geologic Field Web Applications** - Creation of web-based field applications for various tasks, more descriptions are coming soon.
   * See Video here (click on image):
   * [![Geologic WebApps](https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Geologic%20WebApps_Sample.png)](https://youtu.be/dMSfpp2a7Ms)
* **Mineral-Elements-Commodities** - Starting a webpage template which will host geologic mineral with elemental information, commodities linkages, and nomimal year data statistics world-wide. Here is the interactive template shown as a screenshot.
  * <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Minerals_Periodic_Table_Reference2.png" alt="Minerals-Elements-Commodities" width="100%"> 
Implementing a [New Geologic Mapping](https://github.com/jmarcellusc/Earth-Systems-Geologic-Map-Project/) scheme that incorporates modern standards to better reflect utility infrastructure changes, moving beyond outdated conventional mapping practices. I'll be starting to create digital geological map, including interactive websites and products. The current process is the creation of surface models; 2 of material impervious type (canopy and ground); 2 of elevation type (hillshade and elevation contour). These are fundamental models that will overlay geologic information. I'll be starting with geologic maps in the State of Texas.
* **Phase 1** - [Impervious "Permeability" Canopy Model](https://ee-marcelluscampes.projects.earthengine.app/view/hydroimpervious-canopy-surface) - **"Model Created",** this preliminary model data that is the basis for the Hydrologic Impervious Ground Model (currently in progress) and serves in illustrating regions where geologic area is covered by anthropogenic (man-made) materials or natural vegetation canopy.
* **Phase 2** -  [Impervious "Permeability" Ground Model](https://ee-marcelluscampes.projects.earthengine.app/view/hydroimpervious-canopy-surface) - **"Model Created",** this is presented with Phase 1, Canopy-Model. Both the canopy and ground models will be added to a geologic map as an overlay, highlighting anthropogenic (man-made) ground, vegetation canopy only, and water. 
  * Updated: [Overturn Maps Tools](https://www.dropbox.com/scl/fi/mvjrtkn8zqkrv2iwz6ou3/Overture-Maps-Downloader-v1b.zip?rlkey=q9mdeu0skhzc76kjwmys2q66s&st=7tsj5me4&dl=0)
  * Updated: [Map Neatline Tool v3.1](https://www.dropbox.com/scl/fi/tflazuzs75u2nah0zo60c/Map-Neatline-Tool-Public.zip?rlkey=fbbbf66shwcul36ent0o0329u&st=9rs3c1tc&dl=0)
* **Phase 3** - USGS Elevation Data Hillshade - **"In-Progress"** - Will explore USGS and ESA products.
* **Phase 4** - USGS Elevation Data Contours
* **Phase 5** - Project Structure & Administration Creation - **"In-Progress";** Includes generation of neatlines, GeMS project creation, and database schema. The project region is the State of Texas and Mexico (northern) geology.

### Geologic GIS Mapping Toolkits
#### Attribution Series
  - **Geologic Unit Color Toolkit:** [Excel Worksheet](https://www.dropbox.com/scl/fi/slafgkzxl642iut2wqiy0/GeMS-FGDC-USGS_Geologic-Unit-Color-Toolkit.zip?rlkey=ob9pifm19s66l1suq8lrhogcd&st=mmem5azq&dl=0) - GeMS, FGDC, & USGS Compliant
  - **[CMYK Palette Generator](https://github.com/jmarcellusc/CMYK-Palette-Generator) **- [Download](https://www.dropbox.com/scl/fi/2t54rddhgh0hmcnabre4g/CMYK-Color-Palette-Generator.zip?rlkey=mhjynsesdyvvawl4c0w1gb478&st=w4is55to&dl=0) - [Additional Tools Planned]
  - **Class Inspector v2.0** - Verifies and displays all possible properties of a feature class [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  - **Global ID | Domains Tools v1.0** - List out all global ids and domains [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  - **Numeric Increment Tool v1.1** - Options for numeric increment [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  - **Text Correction Tool v3.2** - Options for string modification [Depreciated v1.2] [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  -** Text Inspector v1.3** - List and inspection of strings [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  - **Uniques v1.3** - List of uniques [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)

---

#### Geometric Series
  - **LIGARE Toolkit:** [Older Version 1.3](https://www.dropbox.com/scl/fi/l81drljsjcmrb3zg1wyzu/LIGARE_Toolkit_Public.zip?rlkey=20kiwes0lvh1bijijv8httnpb&st=y96kaee2&dl=0) is available but I am currently updating for code improvement and introduction of new features.
  - **Map Neatline Tool:** [Updated v3.1](https://www.dropbox.com/scl/fi/tflazuzs75u2nah0zo60c/Map-Neatline-Tool-Public.zip?rlkey=fbbbf66shwcul36ent0o0329u&st=nfos1ys2&dl=0) - Fixed path issues and process cleanup.
  - **Reverse Geocoder:** [Download](https://github.com/jmarcellusc/ReverseGeocode)
  - **Line QA Tool** - Tags zigzag and multi part vector linework [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)
  - **Update Editor Tracking** - Option to enable/Disable editor tracking with update injection info [Download](https://www.dropbox.com/scl/fi/u07xhwfoa68lkf8m56wxd/Geologic_Map_Toolkits.zip?rlkey=03agb67lgo85e1yff2f12sr26&st=ayuoluka&dl=0)


#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Geologic Modeling
- **New Project:** Alluvial Geomorphodynamics Toolkit for simulating sediment transport and depositional process. This will eventually include landslide/landfall and flooding applications."

## Lidar Toolkit
  - **LiDAR Toolkit Processer** (Multicore Thread Processing)
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
    - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Lidar%20Toolkit.png" alt="Lidar Toolkit" width="50%">

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Classification Toolkits
* **Google Earth Engine Random Forest Semi-Application**- The reason this can't become a full application is how the platform handles saving and resuming from progress. Neverthless, this semi-application is a powerful random forest engine with various of options. This code is tailored to the USGS National Land Cover Dataset (but can be customize to any means).
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Google%20Earth%20Engine%20-%20Random%20Forest%20Application.jpg" alt="Google Earth Engine Random Forest Semi-Application" width="50%">
   * **METHOD:**  Introduction of AplhaEarth's Google Deep AI Imagery
   * **METHOD:**  Efficient approach in processing random forest of 3 moasic image periods, multistack
     * Example: GEE SMILE Random Forest classification, similar NLCD classification. 
[![GEE Random Forest Classifier Example](https://imgur.com/jq49KYW.png)](https://youtu.be/KmfPY4PzZ20)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Data Extraction
* **Google Geolocator** - Interactive geocode location downloader, currently active utilizing Google Cloud API, **Private Website**.
  * <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Google_Geolocator.png" alt="Google Geolocator" width="80%"> 
* **Advance PDF Utility** - **NEW**, Version 1.1, Fully operation, multi functionality PDF application built for various extractions methods, accessibility checks, and an accompliamnet to Adobe Acrobat. Completed, features include; metadata read/write, bookmarks (links), tag and layers read, language read, scan all hyperlinks, get coordinates, invidible text tags, annotate/comment, PDF mask, PDF/A check, merge PDF, split PDF, mulit-crop, prefomrm OCR page, export PDF to JSON, export all directory PDF to JSON, and extract table. [Download](https://drive.google.com/file/d/1CoMjWirC5Wz-UK3d54ItyJvJg5Gamate/view?usp=sharing)
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Advance%20PDF%20Utility_1.png" alt="Advance PDF Utility" width="50%">
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Advance%20PDF%20Utiliity_2.png" alt="Advance PDF Utility" width="50%">
* **Advance Conda Management** - **UPDATE**, Verion 1.1 (v1a.exe), Repo information and Executable: [Repository](https://github.com/jmarcellusc/Advance-Conda-Mangement) - Please read the Disclaimer Information. Application runs unstable at certain request and I DO NOT recommend running the cleaning processes unless you are 100% sure of its effectiveness. **Disclaimer**: Use this tool at your own risk. The author is not responsible for any data loss, system changes, or instability that may result from its use.
* **NEW** - **A.I. Offline Ollama LLM** - Researching offline use of ollama using Dolphin-llama3. Currently working and also installed AnythingLLM yet the best method for proceeding is to connect programmable codes for multiple types of iterations. Created scripts; (Start_Ollama, Stop_Ollama, Check_Ollama, Ollama_Connect, Ollama_AnythingLLM_Start, Ollama_AnythingLLM_Stop). Next steps is creation of CLI with python (or further menu class system).
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Ollama_Connect.png" alt="Ollama Connect" width="50%">
* **UPDATED:** [AI Prompt Management Program - v2.3](https://www.dropbox.com/scl/fi/6dyipnkja1nfrwjtd1d5h/AI-Prompt-Management-v1d.zip?rlkey=6k8uhbrusqe69syhjxai6asiv&st=by69jip6&dl=0) - Update: Dec, 15 2025. Fixed: Previous version was not saving on import. Dynamic fields option that opens the possibility to save a custom prompt to the local database. Also features; ability to share a database, import a database, appends a user system name, and menu system improvements.
- [Overture Maps Downloader](https://www.dropbox.com/scl/fi/mvjrtkn8zqkrv2iwz6ou3/Overture-Maps-Downloader-v1b.zip?rlkey=q9mdeu0skhzc76kjwmys2q66s&st=9egi4rw7&dl=0) (Update: v1b) - See: [Read Me Information](https://github.com/jmarcellusc/Download-Overture-Maps-Data)
  - NOTE: Only works with release: 24 September 2025	[2025-09-24.0	v1.12.0], schema v1.12.0. Please enter "2025-09-24.0" as the date version. Since Overturn Maps is currently updating their data scheme and storage repositories, I'll wait after 2025 to create an new update. Even so, you are open on aquiring their complete dataset from: [Overturn Maps](https://overturemaps.org/)
- [SAS Converter](https://www.dropbox.com/scl/fi/vppja9koesu2rxiaibr6d/SAS-Converter-v1b.zip?rlkey=haqvy27qxvobalris3ovlcv3n&st=xy1v027i&dl=0) - Source credit:  Jared Hobbs [sas7bdat](https://bitbucket.org/jaredhobbs/sas7bdat/src/master/)
- Download Toolkit v1c - Powerful and moving into a private collection.
- [XML Toolkit v1b](https://www.dropbox.com/scl/fi/4nduxh4hhux7rvugnf920/XML-Toolkit-v1b.zip?rlkey=5k36dvn4skjbdha7wuifax6eb&st=91mwivf3&dl=0) - Working, will update soon. [Minor Issues]
- [VBA Excel Collection Scripts](https://github.com/jmarcellusc/VBA-Excel)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## Hydrological Tools  
 - **Rain-Flood Simulation** - Version 1.0, Rainfall/Flood simulation application completed. Future plans of main platform modification and introduction of advanced options.
 - Algorithm updated, stable, and working on test.
   - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/RainFloodSimulation.png" alt="RainFlood Simulation Application" width="50%">
 - **Depression Identification and Depression Region Enclosure Fill** - Completed, working on literature to document a possible new method
 - General hydrological tools are on paused.

#### [Return to Synopsis Introduction](#work-synopsis-table-of-contents)
---


## Machine Learning Applications
### Imagery Sensing Toolkit 
**Version v1.2** - Introduced: Additional DEM applications such as hillshades, aspects, and curvatures. Also includes several geomorphometry functions from great authors such as Florinsky, Evans, Woods, Jarosław Jasiewicz, and Tomasz F. Stepinski. Improve file and directory picker. Toolkit needs refinement and review on several hard coded parameters (requires the user to input their values), append advance SAR applications, and to include updating several names.
- <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Imagery%20Sensing%20Toolkit_V1_2.png" alt="Imagery Sensing Toolkit" width="50%">

**Version v1.1**; - I would like to extend special gratitude to Jeff Jenness. His invaluable toolkit and documentation have been foundational to my understanding of elevation surfaces over the years. With addition to more hillshade and curvature toolkits, I will be incorporating more of Florinsky methodologys on surfaces as his literature are highly regarded. Not yet available for download.
Adds the following:
  - Spatial Differencing
  - Laplacian Differencing
  - Independent Component Analysis (ICA)
  - Principal Component Analysis (PCA)
  - Uniform Manifold Approximation and Projection
  - DEM Kits: Analysis Surface Metrics
    - Slope: [4-Cell, N-S Gradients, (4,8,Weighted) Gradients]

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


### Machine Learning Toolkit
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
    - Web application is very new and is currently active for canopy (pending low surface vegetations). Several future modifications to include quality check of source imagery selection, checks on interferences, and other improvements are planned. Additionally, with low surface identification, this toolkit will benefit with ideal vegetation algorithm target. 
  - **Updated:** [Wetlands Exploration Toolkit v3.0](https://ee-marcelluscampes.projects.earthengine.app/view/wetlands-exploration-toolkit-v11) - Recently updated.
    - Added 2024, 2025 Years.
    - Added SAR Surface Water Detection.
    - Added New Chlorophyll Detection (Alpha Testing)
  - [Soils Expliratory Tool v1.1b](https://ee-marcelluscampes.projects.earthengine.app/view/soils-exploratory-tool-in-progress-v11b) - [Stable but source inputs are outdated, will require revision and improvement.]
  - [Topographic Terrain Tool v1](https://ee-marcelluscampes.projects.earthengine.app/view/topographic-inspector) - [Stable application, land elevation models are updated by various organizations and will be inspected for updated sources]
  - [Political Boundary v1](https://ee-marcelluscampes.projects.earthengine.app/view/political-country-selection) - [Error in several outdated sources, application requires improvement]
  - [Aerosols Exaiminer Tool v1](https://ee-marcelluscampes.projects.earthengine.app/view/aerosols-examiner-sensing-tool-v10d) - [Issues documented, requires recoding.]
#### ESRI 
  - World Minerals Dashboard- [**! Removed**, Moving project to Google Earth Engine as data hosting with ESRI is costly.]

<br>

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Metadata Applications
- **Accessibility Check Toolkit** - Newly created with checks to single image, single PDF, and a directory scan of images. Will assess contrast check closely aligned to the Web Content Accessibility Guidelines (WCAG). Image checks the following; global contrast, RMS contrast, edge contrast, contrast ratio (WCAG) WCGA Pass, and computes an Overall Score. PDF documents checks the following: text extraction, tags, title set, lanuage definition, and images (and reutrns an overall WCAG/UA Status), (will change to "Metadata Series").
  - Online App website: [Image Contrast Accessibility Check](https://www.jmarcelphotography.com/image-contrast-accessibility-check) is also available for use.
  - Online App Website: [APCA (Lc Score) Check](https://www.jmarcelphotography.com/apca-lc-score) Interactive Lc Score viewer. Created with reference information from: [Myndex/SAPC-APCA](https://github.com/Myndex/SAPC-APCA).
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Accessibility%20Check%20Toolkit.png" alt="Accessibility Check Toolkit" width="50%">
  - <img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Accessibility%20Check%20Image.png" alt="Accessibility Check Toolkit" width="30%"><img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Accessibility%20Check%20APCA%20Lc%20Test.png" alt="Accessibility Check Toolkit" width="30%"><img src="https://github.com/jmarcellusc/jmarcellusc/blob/main/Images/Accessibility%20Check%20PDF.png" alt="Accessibility ChecK Toolkit" width="30%">
 - **XML ESRI Metadata Toolkit**
   - COMPLETED: Pending Link
    - Runs xml extraction into Excel Macro database. Eases in xml replication, modification, and editing, particular to ESRI metadata.
    - Current Batch Tools:
      - Extract Metadata (xml >> excel)
      - Update Metadata (xml >> excel >> xml)
      - Create Metadata (excel >> xml)
  - **PDF Metadata Updater:**
    - COMPLETED: [PDF Metadata Updater](https://github.com/jmarcellusc/PDF-Metadata-Updater) - [Requires [Excel Metadata Database/Form](https://www.dropbox.com/scl/fi/8ucgwe12epf82hv99cjpc/PDF_MetadataDB.zip?rlkey=6ybfdbmpa9md1xoxyqazq47bd&st=gm6o3f5v&dl=0)]
      - Reads Excel Macro database (inventory of pdf metadata) and appends metadata to PDF with advance customizability.
      - Currently single file selection with selectable metadata record injection.
      - Python Small GIS Projects:


#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

<br>

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---


## ESRI
- **[Houston-Galveston Area Council Hurricane Evacuation Dashboard](https://experience.arcgis.com/experience/d24314506471423f98b5252a1b7f5f0f)**
- **Presenting Drones: "Drone Example: Pico De Orizaba"** -  **Link** (Copy and Paste Manually): https://experience.arcgis.com/experience/f1fb7db94c51450c9cc7799ab744d9b2/


<br>
---

<h2 align="center">About Me</h2>
Research in Geological Sciences (Petrology, Geochemistry, Geomorphology, Sedimentation), GIS (Geostatistics, Cartography, Geospatial Data Science, Remote Sensing), Attributional Data Science (Python, VBA, JavaScript)

#### [Return to Work Synopsis & Table of Contents](#work-synopsis-and-table-of-contents)
---

## Contact Information

- Email: **marcelluscampes@gmail.com**
- Website: **https://www.jmarcelphotography.com/**
