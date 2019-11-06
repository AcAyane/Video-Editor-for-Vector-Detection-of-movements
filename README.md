

## Installation and bootstrapping

1. `git clone https://github.com/AcAyane/Video-Editor-for-Vector-Detection-of-movements.git` 
2. `cd Video-Editor-for-Vector-Detection-of-movements`
3. `./install_ffmpeg.sh` (You can also install FFmpeg using the link [here](http://embedonix.com/articles/linux/installing-ffmpeg-from-source-on-ubuntu-14-0-4/))
4. `sudo cp ffmpeg.conf /etc/ld.so.conf.d/ffmpeg.conf && sudo ldconfig`
5. `./compile` OR You can use the compile_command.txt to generate the binary file.
6. mkdir -p output/mv/
7. `./extract_mvs <video-file-path>`.
8. And there you go. The output will be saved in './output/mv/'.


