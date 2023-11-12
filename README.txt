CONTENIDOS DE ESTE ARCHIVO

	* Título y breve descripción del proyecto
	* Partes y estructura del código
	* Instrucciones de uso
	* Autores
	
-------------------------------------------------------

	TÍTULO Y BREVE DESCRIPCIÓN DEL PROYECTO
	
	- Título: SumupVideo
	- Descripción: Este trabajo trata sobre el resumen automático de videos mediante clasificación y agrupamiento utilizando los algoritmos k-means y kNN
	
	
	
-------------------------------------------------------

	PARTES Y ESTRUCTURA DEL CÓDIGO
	
	El código está formado en primer lugar por las bibliotecas y librerías importadas, a continuación, por una serie de funciones declaradas al principio y en orden de su futura ejecución.
	Podemos encontrar las siguientes funciones:
		- captura_videos_y_frames(videoName,imagesFolder)
		- calcula_histogramas(frames)
		- clustering(centros,hist)
		- generar_resumen_frames(kmeans,hist,frames)
		- sacar_vecinos_fluido(videoName,frames_indices,nombres)
		- coger_frames_finales(videoName,ids_finales,imagesFolder)
		- crear_video_resumen(framesFluid,videoName,frameRate)
	La última celda a ejecutar es la llamada a todas las funciones anteriores siguiendo la lógica de de ejecución del script


	
-------------------------------------------------------	

	INSTRUCCIONES DE USO
	
	Para la correcta ejecución del programa habrá que seguir los siguientes pasos:
		1. Ejectuar todas las celdas del script
		2. Introducir el nombre del vídeo con su formato(se tiene que especificar la ruta si el vídeo no se encuentra en la misma carpeta que el script)
		   Ejemplo1 video.mp4
		   Ejemplo2 C:\Users\User1\Videos/video.mp4
		   Esta información será pedida por pantalla.
		3. Introducir la ruta de la carpeta donde se guardarán los fotogramas generados para el resumen.
		   Ejemplo C:\Users\User1\Videos\framesResumen
		   Esta información será pedida por pantalla.
		4. Finalmente el vídeo resumen se encontrará en la misma ruta en la que se encuentra el script con el mismo nombre que el video original seguido de "-Resumen".
		   El propio programa nos indicará por pantalla que el video ya ha sido creado.
		   
		   
		   
-------------------------------------------------------

	AUTORES
	
	- Alfonso Alarcón Tamayo, alfonsoalarcontamayo27@gmail.com
	- Juan Manuel de la Oliva Aguilar, juandelaoliva1@gmail.com
	
	
	
