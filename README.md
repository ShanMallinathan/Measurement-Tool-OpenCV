# Measurement-Tool-Using-OpenCV-c-
This work presents a measurement tool developed using C++ and OpenCV library. It is capable of handling both images and live webcam feed and can be calibrated using the provided template, 1-pound coin, ATM card and manual means.  The measurements have better accuracy while using the provided template for calibration.

The camera feed comes with a side information panel that helps to display the results and provide instructions
<img src = ![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/e7edb1f5-f0eb-48a3-aa5d-07b244211266), alt = "measurement window", class = "center">

Workflow:

1. Make sure that OpenCV C++ is detected by visual studio
2. Run the program
3. Select the input method (static image or webcam). If the image option is chosen, make sure that the image is added to the resource folder (advised to be added within the visual studio environment)

    ![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/b54c1113-b362-4a8c-9b19-fdc40224e6f6)
   
4. Select the type of calibration (1 pound coin, ATM card, rectangle template provided within repo or manual mode with click events)
5. Perform the calibration (click and drag to crop the image if manual mode is not used)
   
   ![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/fa93d9ea-d86d-47c5-9b35-8055a0e1f559)
   ![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/4d7fb996-1452-4093-8d0e-4f28d71aca61)
   
6. Start measuring
7. press 'o' to get the circle radius and r to get the rectangle perimeter automatically (cropping required)

![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/b6fa0b27-466e-466e-81a0-279fc823c647)

<h2>Measurement error rates</h2>

![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/63349697-bf86-47ca-ae4c-eb8b10f2137d)

![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/e18a9087-e4b0-4c16-a759-43d41e462c83)

![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/c87842df-548a-43b6-a6be-fec271c73666)

![image](https://github.com/ShanMallinathan/Measurement-Tool-OpenCV/assets/115928550/51dfe303-2c65-4a1a-924a-023764debb77)
