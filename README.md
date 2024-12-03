# Raspberry Pi - Person and Object Detection

The project involved setting up a Raspberry Pi with the Raspbian OS, connecting devices like a servo motor, button, LED, and USB camera, and ensuring their proper functionality. The **OpenCV** library was installed for image processing, and sample code tested the camera integration. A circuit diagram was created, and custom code was written to control the devices. The project implemented the **MobileNet** neural network for person detection, where the system captured images, detected a person, and controlled the LED—turning it on when a person was detected and off when not.


## Step 1: Connecting Raspberry Pi and Installing the Operating System

1. First, connect the Raspberry Pi to a monitor, keyboard, and mouse, and plug in the power supply. After powering up the Raspberry Pi, follow the on-screen instructions for the initial setup, including selecting the Wi-Fi network and setting the region.

   ![Connecting Raspberry Pi](https://github.com/user-attachments/assets/6200556c-ac6c-44fc-a97a-ae3b19cce79b)


3. Download the Raspbian OS image from the official Raspberry Pi website. Use the Raspberry Pi Imager tool to write the image to the SD card. Afterward, insert the SD card into the Raspberry Pi and boot up the system.


   ![Raspberry Pi Setup_1](https://github.com/user-attachments/assets/e199b50c-8d13-4edd-9b37-4e78e79da090)
   


5. The Raspberry Pi is now ready to use.

   ![Running Raspberry Pi](https://github.com/user-attachments/assets/f0657b83-13d3-47d4-a645-470ea69be73a)


## Step 2: Connecting a Button and LED

1. Connect the button and LED to the GPIO pins on the Raspberry Pi.

   ![Raspberry Pi Pinout](https://github.com/user-attachments/assets/ba876744-26a2-4928-8245-94a1310fb5bb)


3. Write a Python script to control the LED. The program will turn the LED on when the button is pressed.

4. Connect the button and LED, run the script, and test the device. When the button is pressed, the LED should light up.

   ![Testing Button and LED](https://github.com/user-attachments/assets/ae41a65d-5aab-47ef-b019-f4b185916ae5)
  ![Testing Button and LED](https://github.com/user-attachments/assets/cb46046b-122c-49e3-929d-bbe4deb16acd)


## Step 3: Connecting and Setting Up the Servo Motor

1. Connect the servo motor to the Raspberry Pi and use the RPi.GPIO library to control it.

2. Test the servo motor; it should rotate to different positions.

   ![Testing Servo Motor](https://github.com/user-attachments/assets/6d2209cc-6584-4781-bfac-4568b852a2d3)


## Step 4: Implementing Face Detection

1. Install the OpenCV library for face detection.

2. Connect the camera and write code to capture images and detect faces.

3. The program will turn on the LED when a face is detected in the frame. If no face is detected, the LED will turn off.

![Face Detection](https://github.com/user-attachments/assets/25f41a49-3f43-4127-9834-a556b2114f19)


## Part 2: Implementing MobileNet Neural Network on Raspberry Pi

1. Install the TensorFlow library.

2. Use a pre-trained MobileNet model to recognize objects or faces. Download and set up the model to work with the camera.

3. Test the model on the Raspberry Pi. For each frame from the camera, the program will output information about what is visible in the frame.

   ![MobileNet Testing on Raspberry Pi](https://github.com/user-attachments/assets/3aff2ac7-facb-42a1-806a-d8082c6bdfc6)

   ![MobileNet Testing on Raspberry Pi](https://github.com/user-attachments/assets/987ea6a2-7d87-4f73-a7bf-04edfc4fc6e3)
   ![MobileNet Testing on Raspberry Pi](https://github.com/user-attachments/assets/6580160e-de1b-4241-aa80-19e87d7458da)
   ![MobileNet Testing on Raspberry Pi](https://github.com/user-attachments/assets/0cf46e01-d94d-43a8-93d1-ba67483ecad6)




   

