# SIPANGAOv3-semiautonomous

Intrucciones (Español)
En este repositorio tenemos los códigos generados para la obtención de resultados en la propuesta descrita en el manuscrito titulado "Semi-Autonomous Software for Bone Metastasis Detection in Gammagrams as a Precursor to Machine Learning Metastasis Detection Algorithm". 
Los códigos engloban una GUI (Graphical User Interface por su sigla en inglés; o Interfaz Gráfica de Usuario en español) los cuales constan de diferentes códigos para leer o cargar imágenes (imágenes de gammagrafía de medicina nuclear) en cualquier formato (incluyendo DICOM), segmentar, realizar histograma, identificación de ROI (Region Of Interest) para el análisis incluyendo el código que permitía elegir este análisis pensando en algún órgano o hueso; o hacer el análisis en todo el cuerpo. Además de las funciones apagado de pixeles (Pixel Switch Off--PSO), función de umbralización y las rutinas de adición o inyección de falso color que incrementa el contraste (por intervalos de color). 

Este software no pretende reemplazar al médico internista o al especialista que diagnostica, sino que SIPANGAOv3--"Sistema Para Analizar Gammagramas Oseaos"--(nuestra propuesta de software, en su versión 3, v3) tiene convicción de ser un software de apoyo que facilite el diagnóstico marcando un preámbulo en nuestro trabajo para hacerlo completamente autónomo apoyado en Machine Learning. Adicionalmente integramos un archivo guía de SIPANGAOv3 en español y en inglés, es el archivo "userSIPANGAO.pdf".
Anexamos el link donde se encuentran todas las rutinas y la GUI.
https://drive.google.com/drive/folders/1Wb6DbMHNI4IOP_dFs-cZT68-EzEef25c?usp=sharing

Mencionando, que se abre de la siguiente manera:
.- Se carga GUIDE en Matlab y de esta se abre el arcvhivo "Abrir.fig"
.- Se abre directamente el archivo "SIPANGAO.exe", si hay problemas se accede con el paso anterior.

$$
%%
Instructions (English)
This repository contains the source codes developed to obtain the results presented in the manuscript titled “Semi-Autonomous Software for Bone Metastasis Detection in Gammagrams as a Precursor to Machine Learning Metastasis Detection Algorithm.”
The codes include a Graphical User Interface (GUI), which comprises various modules for loading and reading medical nuclear imaging scans (gammagrams) in any format, including DICOM. The software enables image segmentation, histogram generation, Region of Interest (ROI) identification for analysis—either focused on specific organs or bones, or across the entire body.

Additional functionalities include Pixel Switch Off (PSO) routines, thresholding operations, and false-color injection algorithms that enhance contrast through color interval mapping.
This software is not intended to replace the internist or diagnostic specialist. Instead, SIPANGAOv3—“Sistema Para Analizar Gammagramas Óseos”—version 3 (v3) our proposed software, is conceived as a supportive tool to assist in diagnosis, serving as a prelude to future work aimed at achieving full autonomy through Machine Learning. Additionally, we have integrated a SIPANGAOv3 guide file in Spanish and English, which is the file "userSIPANGAO.pdf".
The link to access all routines and the GUI is provided below.
https://drive.google.com/drive/folders/1Wb6DbMHNI4IOP_dFs-cZT68-EzEef25c?usp=sharing

To launch the application, follow these steps:
– Open GUIDE in MATLAB, then load the file named “Abrir.fig”.
– Alternatively, run the executable file “SIPANGAO.exe” directly. If any issues arise, use the previous method.


