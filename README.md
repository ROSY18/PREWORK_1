# PREWORK_1
alberto@Alberto MINGW64 ~
$ pwd
/c/Users/alberto

alberto@Alberto MINGW64 ~
$ cd desktop

alberto@Alberto MINGW64 ~/desktop
$ cd ROSALIA

alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ mkdir Mi_Proyecto

alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ cd Mi_Proyecto

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ mkdir Mis_Datos

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ cd Mi_Proyecto                                                                bash: cd: Mi_Proyecto: No such file or directory

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ cd ..

alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ mv world-university-rankings.zip Mi_Proyecto                                  
alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ cd Mi_Proyecto

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ unzip world-university-rankings.zip                                           Archive:  world-university-rankings.zip
  inflating: cwurData.csv
  inflating: education_expenditure_supplementary_data.csv
  inflating: educational_attainment_supplementary_data.csv
  inflating: school_and_country_table.csv
  inflating: shanghaiData.csv
  inflating: timesData.csv

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ mv cwurData.csv education_expenditure_supplementary_data.csv educational_attainment_supplementary_data.csv school_and_country_table.csv shanghaiData.csv timesData.csv Mis_Datos

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ ls
Mis_Datos/  world-university-rankings.zip

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ rm world-university-rankings.zip

alberto@Alberto MINGW64 ~/desktop/ROSALIA/Mi_Proyecto
$ cd ..

alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ cp -r Mi_Proyecto/ Mi_Proyecto1/

alberto@Alberto MINGW64 ~/desktop/ROSALIA
$ git init
Initialized empty Git repository in C:/Users/alberto/Desktop/ROSALIA/.git/

alberto@Alberto MINGW64 ~/desktop/ROSALIA (master)
$ git add .
warning: LF will be replaced by CRLF in Mi_Proyecto/Mis_Datos/cwurData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto/Mis_Datos/school_and_country_table.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto/Mis_Datos/shanghaiData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto/Mis_Datos/timesData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto1/Mis_Datos/cwurData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto1/Mis_Datos/school_and_country_table.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto1/Mis_Datos/shanghaiData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in Mi_Proyecto1/Mis_Datos/timesData.csv.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in declaraciones honorarios/acuse de cambio de regimen asalariado enero 2020.jsf.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in declaraciones honorarios/acuse de cambio de regimen asalariado enero 2020_2.pdf.
The file will have its original line endings in your working directory

alberto@Alberto MINGW64 ~/desktop/ROSALIA (master)
$ git remote add origin https://github.com/ROSY18/PREWORK_1.git

alberto@Alberto MINGW64 ~/desktop/ROSALIA (master)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/ROSY18/PREWORK_1.git'
$
