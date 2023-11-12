
# SumupVideo - IA 2018

## Overview
SumupVideo, developed by Alfonso Alarcón Tamayo and Juan Manuel de la Oliva Aguilar, is a cutting-edge tool for automatic video summarization through classification and clustering. Utilizing advanced algorithms like k-means and k-NN, it effectively summarizes videos by extracting key frames, ideal for efficient video data processing.

## Code Structure
The Python code is structured with initial library imports followed by a series of functions, executed in their declared order:
- `captura_videos_y_frames(videoName, imagesFolder)`
- `calcula_histogramas(frames)`
- `clustering(centros, hist)`
- `generar_resumen_frames(kmeans, hist, frames)`
- `sacar_vecinos_fluido(videoName, frames_indices, nombres)`
- `coger_frames_finales(videoName, ids_finales, imagesFolder)`
- `crear_video_resumen(framesFluid, videoName, frameRate)`

The final cell calls all these functions, executing the script logic.

## Installation and Usage
1. Ensure Python 2.7 and Jupyter Notebook are installed.
2. Clone this repository.
3. Install dependencies: `numpy`, `opencv-python`, and `sklearn`.
4. Run `SumupVideo.ipynb` in Jupyter Notebook.
5. Enter the video file name and path when prompted (e.g., `video.mp4` or `C:\Users\User1\Videos\video.mp4`).
6. Enter the path for saving generated frames (e.g., `C:\Users\User1\Videos\framesResumen`).
7. The summarized video will be saved in the same directory as the script, with the original video name followed by "-Resumen".

## Authors
- Alfonso Alarcón Tamayo: alfonsoalarcontamayo27@gmail.com
- Juan Manuel de la Oliva Aguilar: juandelaoliva1@gmail.com

