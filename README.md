# 4-custom-web-fonts
how to use custom web fonts

# Reference

* https://github.com/html-css-sessions/4-custom-web-fonts

* https://creativemarket.com/blog/the-missing-guide-to-font-formats



# @font-face for Custom Web Fonts

* The **@font-face** CSS at-rule specifies a custom font with which to display text.

* By allowing authors to provide their own fonts, @font-face makes it possible to design content without 
  being limited to the so-called "safe" fonts (that is, the fonts which are so common that they're 
  considered to be universally available) for eg. Arial, Verdana, Times New Roman etc etc.

* Make it possible to do so without relying on an Internet connection.

* The @font-face at-rule used at the top level of a CSS.

* There are mainly two type of fonts we know **TTF and OTF**.

* **True Type Font** and **Open Type Font**.



# Generating Custom Web Font

* Different browsers support different font formats. You can generate all formats for 
  optimal crossbrowser support with http://www.fontsquirrel.com/fontface/generator.
  
* **TTF:** Raw **True Type file**, designed to look good on-screen.

* **EOT Lite:** **Embedded Open Type** EOTs are only supported by **Internet Explorer**. This EOT type is uncompressed and is the same filesize as a TTF.

* **EOT Compressed:** EOT compressed with LZ compression. File sizes are often smaller than WOFF.

* **WOFF:** **Web Open Font Format** Cross-browser, web-only font format that uses gzip compression. **IE9+, FF3.6+, Chrome 5+**

* **SVG:** **Scalable Vector Graphics** This is an XML format required by **iOS devices before version 4.2.**

* **SVGZ:** This is gzipped version of SVG.
