# SumupVideo - IA 2018

## Overview
SumupVideo, developed by Alfonso Alarcón Tamayo and Juan Manuel de la Oliva Aguilar, is an innovative tool for automatic video summarization through classification and clustering. It utilizes machine learning algorithms like k-means and k-NN to efficiently summarize videos by extracting key frames.

## Code Structure
The Python code comprises a series of functions that are executed in sequence:
- `captura_videos_y_frames(videoName, imagesFolder)`
- `calcula_histogramas(frames)`
- `clustering(centros, hist)`
- `generar_resumen_frames(kmeans, hist, frames)`
- `sacar_vecinos_fluido(videoName, frames_indices, nombres)`
- `coger_frames_finales(videoName, ids_finales, imagesFolder)`
- `crear_video_resumen(framesFluid, videoName, frameRate)`

The final cell in the Jupyter Notebook executes all these functions in order.

## Installation and Usage
1. Ensure Python 3.x and Jupyter Notebook are installed.
2. Clone this repository.
3. Run `SumupVideo.ipynb` in Jupyter Notebook.
4. The notebook will automatically install required dependencies (`opencv-python`, `scikit-learn`).
5. Input the video file name and path when prompted (e.g., `video.mp4` or `C:/Users/User1/Videos/video.mp4`).
6. Enter the path for saving generated frames (e.g., `C:/Users/User1/Videos/framesResumen`).
7. The program will process the video, extract key frames, and create a summarized version, saved in the same directory as the script, named after the original video with "-Resumen" appended.

## Authors
- Alfonso Alarcón Tamayo: alfonsoalarcontamayo27@gmail.com
- Juan Manuel de la Oliva Aguilar: juandelaoliva1@gmail.com
