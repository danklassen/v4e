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

* `-i` the input file name
* `-o` the base output filename (no extension needed... the appropriate ones will be added)
* `-v` an optional video scale string passed to ffmpeg. The default is 480:-1 which scales to 480 wide and maintains the aspect ratio

## Changelog

### 1.0.0
Released 2016-05-13

Initial Release

