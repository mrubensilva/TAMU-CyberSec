# Stegosaurus (100 Points)
## Steghide the Stegosaurus is hiding something behind him with his strange alluring uwu face... Can you find it?
<img width="372" alt="Screenshot 2022-02-04 232810" src="https://user-images.githubusercontent.com/99063625/152629983-413478f2-bd8a-4688-9328-34a510636bb7.png">

![stegosaurus](https://user-images.githubusercontent.com/99063625/152630004-da96c6c5-8e91-4614-ad9e-08b417a99939.jpg)

# Walkthrough

The image of Steghide the Stegosaurus includes a comment in its metadata about steganography, hinting towards the next step of the challenge.

<img width="801" alt="Screenshot 2022-02-04 232955" src="https://user-images.githubusercontent.com/99063625/152630106-877b3e9f-b5ce-4923-8e79-6558e5532022.png">

Using forensics skills, e.g., educated guesses, find a password and a [steganography tool](https://aperisolve.fr/) that can reveal a message hidden in the image. Images run through a steganography tool often need a password in order to be cracked. 

![image](https://user-images.githubusercontent.com/99063625/157351700-d1bd8dc8-983d-41a1-8d74-b85676c2194d.png)

My go-to guesses were: 
```
steghide
stegosaurus
steganography
```
but only ```stegosaurus``` ended up extracting any data.

![image](https://user-images.githubusercontent.com/99063625/157353371-3622fb6d-a4e5-41f9-932d-a90a2d05b177.png)

### The flag is: ```gigem{C4N_YU0_S33_TH3_ST3GG0}```
