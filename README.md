# Green-screen-remover
A green screen is a key component in a film and television production process known as “chroma keying,” in which foregrounded action is combined with separately filmed or constructed background footage. 
The process works by a person in front of bright green backdrops, then isolating and removing that green colour range, and replacing it with a different background. So, the green screen is a large green backdrop placed in the background of a shot to allow for digital effects later. 
Our Green Screen Background Remover System removes the green screen from the original image and adds a static image as a background to the uploaded image and video using OpenCV. It allows for exciting and otherwise-impossible scenarios to be produced, expanding the possibilities.
# STEPS:
1.First load the image you want to remove the green screen from.

2.Then, it will convert the image to HSV color space. HSV color space is a color space that is better suited for representing colors like green.

3.Next, it will threshold the image to isolate the green background. The threshold values you use will depend on the color of your green screen.

4.Finally, it will replace the green background with a black background.


