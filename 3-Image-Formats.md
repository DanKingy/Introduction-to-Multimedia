# Image Formats

* Need to store image data in a consistent manner
* Formats enable standardisation



# Graphical Information

* Two principle methods of representing graphical data:
  * Bitmaps (raster/pixel maps)
  * Vectors



## Bitmaps

* Made up of pixels in a grid
* Work well at representing variations in colours, shades and shapes by are vulnerable to aliasing



# Compression

* Two types of compression that is applied to digital media (audio/video/text etc.):
  * Lossless compression
  * Lossy compression



## Lossless Compression

* Run length encoding
* Compresses data by storing it in a more appropriate way
  * 11111111111111111100000111111111 (4 bytes long)
  * 18, 5, 9 (3 bytes long)
* Guaranteed to not lose important data
* Rarely gives compression better than 2:1



## Lossy Compression

* Removes parts of the data without it being too noticeable
  * The eye is relatively poor in distinguishing differences in chrominance (changes in colour)

<img src="Images/chrominance-difference.png"/>



## GIF

* Graphic Interchange Format
* Palette of only 256 colours
* Uses LZW **lossless** compression



## Animated GIFs

* Produced by defining several images within a GIF file and displaying them sequentially
* Not very good for large/long animations



## JPEG

* Joint Photographic Experts Group
* Lossy compression
* Full colour images (24-bit/true colour)
  * unlike GIFs that are limited to a maximum of 256 colours
* Achieves compression ratios of 30:1



## PNG

* Portable Network Graphics (similar to GIF)
* Lossless compression
* Better quality reproduction than GIF, but no animation
* Transparency



