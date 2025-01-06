# PDF to Video
This is a CLI tool that is written in C++ and is used to convert a `.pdf` to `.mp4` file. It can also convert image sequences into videos.

## Features
- Convert PDF to video
- Convert image sequence to video
- Video animation styles:
	- sequence (slide show)
	- scroll (vertical)
- Chain PDFs or Image Sequences together. (1.pdf + 2.pdf -> output.mp4)
- Change output settings (fps, resolution, duration)

## Dependencies
1. [poppler](https://poppler.freedesktop.org/) - pdf to image
2. [opencv](https://opencv.org/) - image manipulation
3. [ffmpeg](https://ffmpeg.org/) - video rendering backend

## Build System
I'm using the [Meson](https://mesonbuild.com/) build system for my project. It's simple, modern, and easy to learn.
