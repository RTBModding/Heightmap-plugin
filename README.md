# Heightmap-plugin

This plugin is meant to be used with Race Track Builder.<br/>Feel free to [buy me a coffee](https://www.paypal.me/sllxx) if you like it :)

## Installation

Download the [latest version](https://github.com/RTBModding/Heightmap-plugin/releases/latest/download/Heightmap.7z) and unzip all files into your `Race Track Builder\Plugins\Height\` folder. 

## Usage

> [!NOTE]  
> Nothing about "how to create plugins" is public knowledge.<br/>I reverse engineer everything about RTB, so it (and RTB) might contain bugs.

The plugin requires a square, 16-bit grayscale PNG—the same as Unreal Engine requires. You can use tools to create your own imaginary landscape or other tools such as [this](https://manticorp.github.io/unrealheightmap/) to get a real-life map. The **lower** your meter/px scale, the more detail you will get.

There are absolutely no checks in place for file type, file size, bit depth, and whatnot. You can try an 8-bit JPEG and it might work, but I wouldn't try it. 16-bit is used to get 0-65535 different values from a pixel instead of 8-bit's 0-255.

The Z scale is a bit of guesswork. Heightmaps don't have to start at 0 and end at 65535, nor do the pixels in height have to mean anything. Since it's so different from map to map, I left it as a simple scale option you have to experiment with. Here is an example of my settings when importing the entire island of Malta:

<p align="center">
  <img src="https://raw.githubusercontent.com/RTBModding/Heightmap-plugin/main/scrn1.png" width="350">
  <img src="https://raw.githubusercontent.com/RTBModding/Heightmap-plugin/main/scrn2.png" width="350">
</p>

Here is a video: https://www.youtube.com/watch?v=BGlzVsg2T4s
