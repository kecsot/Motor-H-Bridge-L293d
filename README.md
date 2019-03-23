// Go Forward
motorLeft.goForward(255); // 0-255 value. Value of PWM.         Motor max speed = 255
motorRight.goForward(255); 
delay(1000); // wait 1sec

// Go Backward
motorLeft.goBackward(255); // 0-255 value. Value of PWM.        Motor max speed = 255
motorRight.goBackward(255); 
delay(1000); // wait 1sec

// Spin
motorLeft.goBackward(255); // 0-255 value. Value of PWM.        Motor max speed = 255
motorRight.goForward(255); 
delay(1000); // wait 1sec

// Stop (or use motorstop function)
motorLeft.stop();
motorRight.stop();
delay(1000); // wait 1sec
