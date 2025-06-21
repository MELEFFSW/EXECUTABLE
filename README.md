# MELEF FSW PROJECT EXECUTABLE (MELEF FSW)

<div style="text-align: center;">
<img src="https://github.com/MELEFFSW/EXECUTABLE/blob/master/ASSETS/GraphicalAbstract.png" alt="MELEF FSW MODEL" width="300" style="display: inline-block; float: none;">
</div>

 
Welcome to the MELEF Fresh-Salt Watershed repository! This collection provides an installation package and a user manual.
 
## ✨ What is MELEF FSW?
 
In distributed hydrological modeling, there are commercial reference codes such as Mike She, Mike Basin, Cathy, ModFlow, 
Feflow among some other models. The development of physical based distributed numerical technologies, which are an alternative to other commercial solutions, are 
usually not relevant when they do not provide confident solutions to most hydrological processes. In this context, researchers from the University of 
La Coruña and the University of Guanajuato join forces to develop a numerical solution with a series of qualities and capabilities that distinguish it from other codes. 
This approach allows solving the groundwater and surfacewater flows of a hydrological region in an integrated way for most hydrological processes. 
The FreshSaltWatershed (FSW) model, as one of MELEF models (Modèles d'ÉLÉments Finis, for its acronym in French), considers novel capacities to solve the continental 
and coastal regional groundwater and surfacewater flows in an integrated way, as most regulation problems and seawater intrusion through an immiscible interface of fresh-salt water.

## ✨ Installation

The installation package include the following:

- The MELEF FreshSaltWatershed (FSW) User Interface was created as stand-alone executable of Matlab R2012a (7.17, 32 bits) for Windows. As it is a stand-alone executable, 
it allows running the program through the Matlab Runtime R2012a, version 7.17 with 32 bits. The Matlab Runtime can be downloaded for free from the following link: 
https://la.mathworks.com/products/compiler/matlab-runtime.html. If required, download and install the Runtime in the correct version previously to install MELEF FSW. 
The User Interface will not run without the right version of Matlab / Runtime installed. 

- The numerical model MELEF FSW.exe is included in the installation and has been created as a stand-alone 32 bit Fortran executable for Windows. 

- GIS Toolbox and Python Scripts, are included for QGIs or ArcMap. Follow the instructions in the PDF manual to include these Toolbox in the GIS software.

- Manuals in PDF and CHM formats are included in the installation folder.

Respect to the GIS Toolbox for QGIS and ArcGIS (ESRI) platforms, it is developed with Python Scripts. For ArcMAP the GIS Toolbox works on versions 10.1 to 10.8.2. 
For QGIS the Python Scripts were developed in version 3.10 (A Coruña) and higher versions of QGIS would work with the MELEF FSW Toolbox.
Regarding the operating system and the characteristics of the processing equipment, it should be considered that ArcGIS or QGIS are required for management 
and transformation of spatial information that demands specific characteristics for graphic design. Whereas the User Interface through the Matlab Runtime 
can be less demanding of CPU processing or graphics, the calculation time of MELEF FSW model will depends directly on the processor capacity. 
Therefore, the following minimum characteristics are suggested:

OPERATING SYSTEM: Windows 32/64 bits XP, Server, 7, 8, 10, 11
PROCESSOR: Intel Core 2 duo or higher (equivalent platforms) with at least 2 GHz of clock speed.
RAM: > 8 GB
GRAPHIC CARD: > 64 MB (required for ArcGIS or QGIS geoprocessing tasks)

It is recommended to start the user interface installation using administrator permissions. To do this, right click on the executable package and select run as administrator. 
This prevents known issues related to access permissions and editing databases managed by the program during operation. In Windows 7 and later versions, you may need to 
go to the task scheduler to run the interface as an administrator.

When starting the user interface, it will take a moment to display (approximately 1 minute), as Matlab Runtime must first be loaded and then the user interface must be executed.

## ✨ Contact information

DEVELOPERS: Dr. Francisco Padilla Benítez and Dr. Jesús Horacio Hernández Anguiano.
CONTACT: francisco.padilla@udc.es and horacio.hernandez@ugto.mx.
COLABORATORS: Dra. Yanmei Li; Dra. Xiaoxiao Zha; Dr. José Alfredo González Calderón

## ✨ Publications

1. Numerical modelling of surfacewater/groundwater flows for freshwater/saltwater hydrology: the case of the alluvial coastal aquifer of the Low Guadalhorce River, Malaga, Spain (https://link.springer.com/article/10.1007/s00254-007-0977-2)
2. A numerical solution to integrated water flows: Application to the flooding of an open pit mine at the Barcés river catchment – La Coruña, Spain (https://www.sciencedirect.com/science/article/abs/pii/S0022169412008578)
3. A Numerical Solution for the Integrated Analysis of Water Resources Management: Application to the Mero River Watershed,  La Coruña, Spain (https://file.scirp.org/pdf/JWARP_2015071713384131.pdf)
4. Application of a numerical model designed for integrated watershed management (https://www.witpress.com/Secure/elibrary/papers/WS15/WS15011FU1.pdf)
5. Improvements in Mero River Basin Water Supply Regulation Through Integration of a Mining Pit Lake as a Water Supply Source (https://link.springer.com/article/10.1007/s10230-015-0378-9)
6. Modelling Integrated Extreme Hydrology (https://www.witpress.com/elibrary/sse-volumes/6/3/1362)
