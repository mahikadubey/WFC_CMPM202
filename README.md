# WFC
WaveFunctionCollapse Project for CMPM 202 W19 - Creation of some artifacts using WFC in Python (using https://github.com/ikarth/wfc_python). Modified samples.xml and sample images added above.   

Sample pixel art images created manually using PixilArt (https://www.pixilart.com/)

# How to Run  
1. Sample pixel art image (eg. Islands.png) put in folder sample2/
2. In samples.xml, add a line indicating tilesize for sampe image: `<overlapping name="Islands" N="3" periodic="True"/>`
3. Instantiate an OverlappingModel using the sample image: `a_model = OverlappingModel(WIDTH, HEIGTH, SAMPLE_NAME, N, PERIODIC_IN, PERIODIC_OUT, SYMMETRY, GROUND)`  

## Flat Maps and Terrains:  
Map structure is better preserved with larger tile size (N=3), especially in images with clear boundaries around certain objects.  
  
  
![](Maps.png)  
  
  
## Persian Patterns: 
Images with a lot more details ended up being tiled entirely (with N=3. With N=2, tilesize is too small to replicate complex patterns). Simpler patterns lead to more interesting generated artifacts.  
  
  
![](Tiles.png)
