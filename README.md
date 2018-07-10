# 4-custom-web-fonts
how to use custom web fonts

# @font-face for Custom Web Fonts

* The @font-face CSS at-rule specifies a custom font with which to display text.

* By allowing authors to provide their own fonts, @font-face makes it possible to design content without 
  being limited to the so-called "safe" fonts (that is, the fonts which are so common that they're 
  considered to be universally available) for eg. Arial, Verdana, Times Now etc etc.

* Make it possible to do so without relying on an Internet connection.

* The @font-face at-rule used at the top level of a CSS.



# Online tool to convert font to web compatible 
    https://www.fontsquirrel.com/    



# Generating Custom Web Font

* Different browsers support different font formats. You can generate all formats for 
  optimal crossbrowser support with http://www.fontsquirrel.com/fontface/generator.
  
* TTF: Raw TrueType file, designed to look good on-screen.

* EOT Lite: EOTs are only supported by Internet Explorer. This EOT type is uncompressed and is the same filesize as a TTF.

* EOT Compressed: EOT compressed with LZ compression. File sizes are often smaller than WOFF.

* WOFF: Cross-browser, web-only font format that uses gzip compression. IE9+, FF3.6+, Chrome 5+

* SVG: This is an XML format required by iOS devices before version 4.2.

* SVGZ: This is gzipped version of SVG.