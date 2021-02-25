# Image Steganography Using Python and tkinter

#### Steganography project with gui. Hides text inside image. Least Significant Algorithm (LSB) is used to hide the text.

## Steganography

Let’s understand what is steganography, digital images, pixels, and color models.

### What is steganography?

> [Steganography](https://en.wikipedia.org/wiki/Steganography) is the practice of concealing a file, message, image, or video within another file, message, image, or video.

### What is the advantage of steganography over cryptography?
> The advantage of steganography over [cryptography](https://en.wikipedia.org/wiki/Cryptography) alone is that the intended secret message does not attract attention to itself as an object of scrutiny. Plainly visible encrypted messages, no matter how unbreakable they are, arouse interest and may in themselves be incriminating in countries in which [encryption](https://en.wikipedia.org/wiki/Encryption) is illegal.

In other words, steganography is more discreet than cryptography when we want to send a secret information. On the other hand, the hidden message is easier to extract.


Here in this code we give image and text to be concealed in an image and press *Encode*. To  retrieve the data press *Decode*.
## Encode Preview:
![alt text](https://github.com/Helium-He/Image-Steganography/raw/master/Image%20Steganography/raw/Encode.gif)
## Decode Preview:
![alt text](https://github.com/Helium-He/Image-Steganography/raw/master/Image%20Steganography/raw/Decode.gif)
 
 ## Requirements
 * Python
 * tkinter
 * Pillow PIL 

 ## How to run?
 ```
 git clone https://github.com/msz-coder/image-steganographer.git
 cd image-steganographer
 pip3 install -r requirements.txt
 python3 steganographer.py
 ```

#### Feel free to Help and learn. (^_^)
### Note: This software is best compatiable with .png images 
