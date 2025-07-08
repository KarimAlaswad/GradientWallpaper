# GradientWallpaper
This is inspired by [whatamesh](https://whatamesh.vercel.app/) Gradient.js library but instead of 4 pre-defined gradients, it loops through all the hexadecimal colors with 100% saturation.

# Usage  
1- clone or download the repo as a zip  
2- drag and drop the Gradient.html into [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) (Import Offline Wallpaper) or [Lively Wallpaper](https://github.com/rocksdanister/lively)  
3- enjoy 🎉

for manual import with Wallpaper engine:  
  Click on "Open Wallpaper" bottom left, then choose "Open offline wallpaper (animated)"

Make sure to keep Gradient.js and Gradient.html in the same folder!

https://github.com/user-attachments/assets/be3f61f9-7198-4da1-b0db-3061badfd952

# Configuration
In line (35-37) in Gradient.js, you can change the hue, saturation and lightness to include even wider color space but it tends to be more paler, this file ships with 100% saturation by default.  

To change the colorChangeInterval to change the speed of the color swap, in line 308 change e(this, "colorChangeInterval", 3000), // 3 seconds per color

# Todo  
I might try to implement these configurations to be done through Lively GUI without changing it through the file.
