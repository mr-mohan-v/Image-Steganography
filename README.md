# Image-Steganography:

Steganography is not a new or modern technique. Painters and artists across the globe have made use of this technique to conceal signatures and other hidden messages within their art or paintings.
   <br/><br/>Today, digital steganography is the most common way of concealing information from third parties.
   <br/><br/>Image Steganography refers to the process of hiding data within an image file. The image selected for this purpose is called the cover image and the image obtained after steganography is called the stego image. 

 
# Description:
You hide an image inside another image by encoding it into the least significant bit positions of a subset of pixels in another image. The encoded image can be afterwards decoded and recovered without any information loss

# Encoding :
•	Opens two specified images, an image we want to conceal and an image we want to use for concealing,
<br/>•	Hides the image information in the binary pixel values of the other image and saves the resulting image in a specified location or the default location if no location is specified.
<br/>•	The number of pixels in the image used for hiding an image must be at least (2 * number of pixels in the image to be hidden + 1)

# Decoding :
•	Opens an image which contains information of a hidden image, recovers the hidden image and saves it in a specified or default location. 
<br/>•	Extracts a sequence of bits representing a sequence of binary values of all pixels of the hidden image.
<br/>•	The information representing a hidden image is stored in the 4 least significant bits of a subset of pixels of the visible image.


# Application of image Steganography :
•	Defense organisation: security from enemies
<br/>•	Intelligence Agencies: security of person’s private information
<br/>•	Government Agencies: store critical data like criminal record
<br/>•	Smart identity cards: personal information is embedded into photo
<br/>•	Medical: patient’s details are embedded within image


# Conclusion :
   <br/>Thus, this encrypting technique helps to send a image with a secret image inside it to somebody.
   <br/>If done correctly this is undetectable to the naked eye and can be difficult to detect even using the right tools. 
  <br/>For even more security, the secret data can (and should) be encrypted first. 
 <br/>This technique has allegedly been used by Al Qaeda to pass secret messages.
