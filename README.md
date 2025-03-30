# Video Compressor & Uploader

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/james-ngaihte/Compress-Download-Videos-with-Google-Colab/refs/heads/main/Compress-Download%20Videos.ipynb)

This Colab notebook compresses videos using FFmpeg and uploads them to Google Drive.

## Features
- Mounts Google Drive for file access  
- Compresses videos using FFmpeg  
- Downloads Videos using various tools (including wget, m3u8 , and bunkr downloader)
- Uploads the compressed file to Google Drive
- File Management Capability if required by user.

## How to Use
1. Click the **"Open in Colab"** button above.  
2. Run the first cell to mount Google Drive.  
3. Follow the steps to select, compress, and upload,download a video.
4. If user needs managing their files within colab itself (eg.move files within folders or move a file from colab to a mounted drive) , they can choose their desired option and execute it.  

## Requirements
- Google Colab  
- FFmpeg installed (`apt-get install ffmpeg` on Linux)  
- Google Drive API enabled  
