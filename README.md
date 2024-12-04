# Statistical-analysis-of-spatial-data-with-R-and-QGis
Lesson: User manuals by the author represent the teaching of a  module of a postgraduate course on "Educational Indicators", of statistical analysis of spatial data, through the use of the  statistical language R and the geographic information software QGis.

-------------------------------------------------------------------------------------------------------------------------------------------
Statistical analysis of spatial data with R and QGis.
"Análisis estadístico de datos espaciales con R y QGis".
                  Version 1.0
-------------------------------------------------------------------------------------------------------------------------------------------
          Theoretical Physics and the Cosmos Department
      Signal Theory, Telematics and Communications Department
---- Andalusian Institute of Geophysics and Prevention of Seismic Disasters ----------
      Granada University (Ugr), Granada, Spain
-------------------------------------------------------------------------------------------------------------------------------------------

    Author: Ligdamis A. Gutiérrez PhD (1,2,3)
    Managua, Nicaragua 2020

Institutions associated:

(1) Department of Theoretical Physics and Cosmos. Science Faculty. Avd. Fuentenueva s/n. University of Granada. 18071. Granada. Spain.

(2) Andalusian Institute of Geophysiscs. Campus de Cartuja. University of Granada. C/Profesor Clavera 12. 18071. Granada. Spain.

(3) American University (UAM). Managua, Nicaragua

'' WARNING: Do not modify or edit the documentation material without the author's permission.
   If you use this documentation, please indicate and reference the author and the institutions he represents.
  
-------------------------------------------------------------------------------------------------------------------------------------------

Acknowledgment:

We thank the management of the Postgraduate and Continuing Education Directorate (DPEC), from the American University (UAM), 
allowing the teaching of this documents as part of a module of the postgraduate course in Statistics Systems and Educational Indicators. 
As well as being a member of the jury for the defense of the final project for the postgraduate degree in Statistical Systems 
and Educational Indicators.

-------------------------------------------------------------------------------------------------------------------------------------------

Introduction:

Dear User:

This file contains information related to Documentation for four modules on the topic:
 
Statistical analysis of spatial data with R and QGis.
"Análisis estadístico de datos espaciales con R y QGis".

Please read it carefully before starting work.

In the same way, it is recommended to review the contents of the manual attached to the documents, in order to become familiar with the different actions that can be carried 
out, through the elements of system management.

The codes and examples contained in the user manuals have been developed in R language and QGis Georeferencing Software (Geographic Information System).
Both software, R and QGis, are easy to use, free, open source. 

I) *** R LANGUAJE ****

The R languaje can be downloaded from the website:

https://www.r-project.org/

The languaje works the same on Windows, Linux, Mac systems.

It works on 32 and 64 Bit Systems (x86, win64), under Windows (7, 8, 10, 11).
This Software has been tested on Linux systems on Ubuntu 20 and the macOS for Mac System.
Additionally, should work without problems in other similar Linux systems like: Debian, Ret Hat, Fedora, SUSE, etc.

A detailed explanation of installing R via CRAN is found in "module I" as part of the accompanying documentation and manuals.

The R version used for the examples and accompanying documentation is 3.6.2. 
However, more update versions are currently available, with which the examples work without any difficulty. 
On the other hand, it would be necessary to observe whether there are any changes in the codes in the new versions, 
to adapt them to the examples and work proposed in the documentation.

In the user manual documents included in this work, both the installation and the use of the "RStudio" and "RCmdr" subprograms are detailed; 
in the examples included in the documents, the user will be able to easily learn how to effectively manage and use these subprograms.

II) *** QGis Software ****

QGis is a software that provides a work environment for professional geographic information. It is open source and free. 
Its main feature is that it allows the creation, analysis, editing of graphics, maps and publication of geospatial information.

The documentation can be downloaded from the website:

https://www.qgis.org/

The user manuals detail the installation, configuration and use process of this software.

The QGis version used for the examples in this material at the time of its creation was "Qgis 3.10 A Coruña". 
However, the user may find more updated versions of this software without having any involvement in the examples 
used by the author in the documentation. Please note that some instructions may vary according to updates, 
so it is appropriate to review the documentation for the version to adapt the examples.

-------------------------------------------------------------------------------------------------------------------------------------------
GENERAL CONTENT INDEX: Contents of each module
-------------------------------------------------------------------------------------------------------------------------------------------

The main documents of the user manuals are designed and written in Spanish and are composed of four modules, which are the following:

a) Module 1: Introduction to R and QGis and Installation, configuration and basic use of R and its interfaces.
             (Introducción a R y QGis e Instalación, configuración y uso básico de R y sus interfaces).

b) Module 2: Introduction to descriptive and inferential statistics and basic use with R and its interfaces.
             (Introducción a la estadistica descriptiva e Inferencial y uso básico con R y sus interfaces).

c) Module 3: Introduction to QGis, its use, interaction with R and analysis of discrete spatial data.
             (Introducción a QGis su uso, interacción con R y análisis de datos espaciales de tipo discreto).

d) Module 4: Introduction to the analysis of continuous spatial data Geostatistics and aggregated or regional spatial data.
             (Introducción al análisis de datos espaciales de tipo continuo Geo-estadística y datos espaciales agregados o regionales).

The development, content, design, presentation and writing of these four user manuals by the author represent the teaching of a 
module of a postgraduate course on "Educational Indicators", of statistical analysis of spatial data, through the use of the 
statistical language R and the geographic information software QGis, taught to technical and managerial workers of three ministries 
of the Government of Nicaragua, offered by the American University (UAM), through the Postgraduate and Continuing Education Directorate (DPEC), 
in Managua, Nicaragua, in January 2020.

NOTE: Each module within the user manual contains a detailed table of contents that helps the user to learn and improve 
their knowledge of both the language and the geographic information software. Please consult the user manuals contained in this work.

-------------------------------------------------------------------------------------------------------------------------------------------
MAIN OBJECTIVE OF MODULES DOCUMENTATION
-------------------------------------------------------------------------------------------------------------------------------------------

Through simple, user-friendly and easy-to-use explanations and examples, each module represents the use of a language and software 
that provides statistical data analysis tools, combined with the creation of maps with which georeferencing points of statistical values ??can be used.
It is very useful for those who are dedicated to data management and who seek to represent statistical data analysis and practical results 
in a much more useful way in the economic, educational, financial, etc. fields.
   
-------------------------------------------------------------------------------------------------------------------------------------------
INSTALLATION COMMENTS
-------------------------------------------------------------------------------------------------------------------------------------------

The R language and QGis works fine on Windows (XP, 7, 8, 10, 11) 32-bit and 64-bit systems.

The system it’s designed to work in multiplatform.
It is allowed by programming in R languajes On Windows, Linux and Mac systems without problems.

-------------------------------------------------------------------------------------------------------------------------------------------

Soon, in a new version or update of the current version (1.0), new module may be added, containing several types of analysis, functionalities or more methods, 
other analysis tools and more examples.

** THEY WILL BE AVAILABLE FOR DOWNLOAD IN THE FUTURE **
Sincerely, Best Regards. Ligdamis A. Gutiérrez E. PhD.

-------------------------------------------------------------------------------------------------------------------------------------------
