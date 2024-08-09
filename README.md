# Heightmap-plugin

This plugin is meant to be used with Race Track Builder.

## Installation

Download the latest version and unzip all files into your `Race Track Builder\Plugins\Height\` folder. 

## Usage

The plugin requires a square, 16bit grayscale png - the same as unreal engine requires. You can use tools to create your own imaginary landscape or other tools such as [this](https://manticorp.github.io/unrealheightmap/), to get a real life map. The **lower** your meter/px scale, the more detail you will get.

There are absolutly no checks in place for filetype, file size, bitness and what not. You can try an 8 bit jpg and it might work but i wouldnt try it. 16Bit is used to get 0-65535 different values from a pixel instead of 8Bits 0-255.


The Z scale is a bit of guesswork. Heightmaps dont have to start at 0 and end at 65535 nor does the pixels in height have to mean anything. Since its so different from map to map, i left it as a simple scale option you have to experiment with. Here is an example of my settings when importing the entire island of Malta:

<p align="center">
  <img src="https://raw.githubusercontent.com/RTBModding/Heightmap-plugin/main/scrn1.png" width="350">
  <img src="https://raw.githubusercontent.com/RTBModding/Heightmap-plugin/main/scrn2.png" width="350">
</p>