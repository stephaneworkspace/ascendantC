# Calcul of ascendant
# By Stéphane Bressani
````
cd lib
make dylib
gcc -dynamiclib -undefined suppress -flat_namespace asc.o -o ../ascendant.dylib
````
