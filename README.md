# heartrate
a simple pure data patch to visualise heartbeat with a webcam

HOW TO USE IT?
Turn the DSP on and press your webcam with your finger.

HOW DOES IT WORK?

During a hearbeat cycle, the blood circulation makes slightly change the color of your skin.
This patch measures these variations when you press the webcam with your finger.
For each frame, it just the mean red pixel value of the image.
This value is then filtered and rescaled. This processing helps to catch the relevent information. That's it.
