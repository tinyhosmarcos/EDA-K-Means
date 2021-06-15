## K-Means  
Usando la libreria SFML para visualizar los puntos y clusters, se requiere los siguientes parametros(por motivos del tamaño del archivo no pude descargar el dataset,asi que use un dataset mas pequeño).  
 **Nombre del archivo**:nombre del dataset.  
 **Numero de clusters**:Numero de cluster a construir.  
 **PARA COMPILAR**  
Se necesita previamente instalar las bibliotecas necesarias de SFML y ejecutar los siguientes comandos:  
1. g++ -c main.cpp KmeansCode.hpp  
2. g++ main.o -o sfml-app -lsfml-graphics -lsfml-window -lsfml-system  
3. ./sfml-app
