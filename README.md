# File-Upload-Techniques
Different types of Unsafe File Upload techniques are listed 

###### File Upload ##########

1) simple .php upload with simple code

2) Multi functional web shell like: b347k

3) Reverse Webshell: pentester monkey reverse shell netcat listening

4) File Upload to XSS
    -> upload xss.swf
    -> upload xss.svg
  * -> DOS with resize image
  * -> Pixel flood (increase pixel and dimensions of the file programmly)
  * -> GIF flood
    -> PNG size compression

5) Bypass content verification
    -> Different extension using
    -> MIME type manipulation
    -> Add Comments in the image data 

6) Bypass file name:
    -> change the extension of the file
    -> adding null bytes to the file name
    -> double extensions

7) Content_length bypass:
    -> upload very short file / small code
