# BlinkActivatedAlertButton
__A simple website where a button can be triggered by an eye blink. Hands free.

Here you can find the html, css and javascript files to run the website locally and the cpp code for arduino.
The arduino code was taken from [another repository](https://github.com/upsidedownlabs/BioAmp-EXG-Pill) created by upsidedownlabs, the company that built the board for signal acquisition that I used.
On the other hand, the html, css and javascript code were written by myself with the help of a friend for the first project of NeuroTechSorbonne, a neurotech student club at Sorbonne University which we founded.

#Requirements: It only works on google chrome since it uses its Web Serial API. Other than that, it requires three electrodes, an arduino uno board and a board for signal acquisition. Refer to the [upsidownlabs repository](https://github.com/upsidedownlabs/BioAmp-EXG-Pill) for the hardware setup.

#Review: It works well but is a little bit too sensitive. Also, it's an educational project and has no real application possible as eye blinks happen all the time although we don't want to click the button all the time! One way to solve this issue could be to use deep learning to help distinguish deliberate eye blinks from unconscious ones.
