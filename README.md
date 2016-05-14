# v4e
A simple bash script to convert videos to various formats for html5 video using ffmpeg. This will output the formats based off the video for everybody (http://camendesign.com/code/video_for_everybody) strategy.

## Usage

### Installation

1. clone the repo
`git clone https://github.com/danklassen/v4e.git`
2. symlink to the v4e script with something like (modify it for your environment)
`ln -s ~/apps/v4e/v4e ~/bin/`
3. convert your video files
`v4e -i input_file.mp4 -o output_file_name`
4. Profit?

### Options

* `-c` capture a still cover photo (use -t to seek to a specific point in the video)
* `-d` input directory (required if input file is omitted)
* `-i` input file (required if directory is omitted)
* `-t` seek to a specific timestamp for a screen capture (defaults to '00:00:05.000')
* `-o` output file (required)
* `-v` video scaling (defaults to 480:-1 to preserver aspect ratio)

## Changelog

### 1.0.1
Released 2016-05-14

* added in the `-d` directory parsing option
* added in the `-c` coverphoto flag
* added in the `-t` coverphoto timestamp option

### 1.0.0
Released 2016-05-13

Initial Release

