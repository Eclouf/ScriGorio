# <p align="center">![image](https://github.com/Eclouf/ScriGorio/blob/1456c19bdc842db2afd18a436fd1cbad3e6ebcb9/exemple.jpg)</p>

# ScriGorio

ScriGorio is a configuration for using [Gregorio](https://github.com/gregorio-project/gregorio) with [Scribus](https://github.com/scribusproject/scribus). Its aim is to allow you to create Gregorian partitions directly from the Scribus interface, without the need for extensive Latex knowledge. The xml configuration file originally comes directly from the Gregorio project and can be found [here](https://github.com/gregorio-project/gregorio/blob/ec7c886cb424f89c64983831fcd80cf187f5b306/contrib/900_gregorio.xml).


##  Install Dependencies  
To use ScriGorio, you need to install scribus, a Tex distribution, and install Ghostscript.

### Install Scribus :

Download Scribus [here](https://www.scribus.net/downloads/)

### Install Ghostscript :

Download Ghostscript [here](https://www.ghostscript.com/releases/gsdnld.html)

### Tex distribution :
 
- [MacTex](http://www.tug.org/mactex/) for MacOs.
- [MikTex](https://miktex.org/) for Windows, MacOs, Linux.
- [Tex Live](https://tug.org/texlive/) for Windows, MacOs, Linux.
- ...

Load the GregorioTex module

### Install ScriGorio : 
#### For Windows : 

```bash
explorer C:\Program Files\Scribus <version number>\share\editorconfig
```
copy and paste file 901_scrigorio.xml
