# DBScan-PCL-Optimized

This project is taken from: Navarro-Hinojosa, Octavio, y Moisés Alencastre-Miranda. "DBSCAN modificado con Octrees para agrupar nubes de puntos en tiempo real." 
Research in Computing Science, Vol. 114: Advances in Image Processing and Computer Vision, pp. 173–186, 2016.

News:
* Added arguments param option
* Added pcl visualizer
* Deleted Glut visualizer
* Added cluster saving method
* Added cluster coloring method
* Replaced the input file from csv to txt

## Input file structure

file.txt: x y z

-------------------
## Compile
* Create a "build" folder

in the main folder:

	  - cd build  
	  - cmake ../src/
    - make
       
        	 
### Test

    ./dbscan <txt file> <eps> <min Pts> <max Pts>



