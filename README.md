1. Description

What lies beyond an image's edges? There are many ways to employ randomness in order to achieve an interesting, reminescent, "ordered chaos" approximation of the starting image, and beyond.

Noise: given a sufficient number of monkeys, each with a typewriter, one will eventually write a Shakespearian play, word for word. What are the words coming afterwards?

Weave: each column and row of pixels composing an image can be thought of as a sinusoidal wave of some arbitrary complexity. This wave can be furthered backwards and frontwards, thus establishing a "weave"-type appearance, with no beginning and no end.

---

2. Installation instructions

For windows:  
	- download and extract the files  
	- install java on your machine  
	- run “java -jar InfinimageEditor.jar” in a command shell at the appropriate file location.

For linux:  
	- download and extract the files  
	- install java on your machine  
	- run “java -jar InfinimageEditor.jar” in a command shell at the appropriate file location.

---

3. Software instructions

All patterns are generated from training upon a initial image.

Noise pattern

i- Load an initial image from your computer.
ii- Iterations: the number of times a given entity is provided a seed such that it might improve overall fitness. This is the primary 'speed of execution' versus 'quality of approximation' factor.
Use seed: wether or not to use a pre-determined initial seed.
Seed: using a specific seed will systematically generate the same configuration of entities.
iii- Greyscale: wether the image should have color or not.
Training Set: wether to display the approximation of the initial image or not in the result.
Centered: wether the approximation of the initial image is centered or not. If not, it appears at the top left of the result.
Repeat X: the number of vertical repetitions of the approximation.
Repeat Y: the number of horizontal repetitions of the approximation.
Set Alpha: wether or not to use a fixed alpha value (recommended).
Alpha Value: the fixed alpha value (recommended at "1").
iv- Save the resulting image as a png or a (non-animated) gif.

Weave pattern
i- Load an initial image from your computer.
ii- Iterations: the number of times a given entity is provided a new configuration such that it might improve overall fitness. This is the primary 'speed of execution' versus 'quality of approximation' factor.
Engine: the number of simultaneous sinusoidal waves running along a single row or column of pixel.
Use seed: wether or not to use a pre-determined initial seed.
Seed: using a specific seed will systematically generate the same configuration of entities.
iii- Greyscale: wether the image should have color or not.
Scale X: the lenght of the rows.
Scale Y: the length of the columns.
Offset X: the position of the output upon the vertical continuum of the weave.
Offset Y: the position of the output upon the horizontal continuum of the weave.
Set Alpha: wether or not to use a fixed alpha value (recommended).
Alpha Value: the fixed alpha value (recommended at "1").
Corner Fill: the greyscale value used to paint the parts of the canvas not covered by the weave (black is 0.0, white is 1.0).
iv- Save the resulting image as a png or a (non-animated) gif.


---

4. Bugs/updates

There will be no fix nor maintenance of any kind.
