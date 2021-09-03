# SignInterpreter
A device to convert Hand Sign to Audio output
Sign-interpreter
![WhatsApp Image 2021-09-03 at 7 13 36 PM](https://user-images.githubusercontent.com/46946896/132015270-82741eae-f47b-4276-8ce7-fc85fefddcc6.jpeg)


Introduction
Today 1 in 20 people are speech impaired, i.e. they cant talk or hear. The speech impaired society uses sign language to overcome this challenge among themselves, but when it comes to communicating with the rest of the society, it gets more challenging. A very small sector of the society who aren't speech impaired can understand and communicate with sign languages.

Motivation
The speech impaired part of the society faces a colossal challenge of communication with the society they live in. It is estimated that in the year 2050, 1 in 10 people are expected to be speech impaired. 

Our device is directed for the benefit of this speech impaired society.
The device is a wearable glove with sensors mounted on it to capture the real time data. The device, with the aid of sensors and algorithms, tracks the exact movement and position of the hand when it's used, and converts the real time gestures to speech immediately as if they are communicating in real time with the help of the device.



Solution
The project aims for the benefit of the speech impaired part of the society allowing them to communicate easily with the rest of the society.
The core features of the device are,
One Time investment and affordable 
Customisable to any sign languages
Portable and easy to use
Connectivity to smartphones.

These core features make our device much more favourable and bring hope and provide a unique ability to the speech impaired society to express their views and thoughts with the society. 


Working
 The device is a wearable glove with sensors like flex sensors and accelerometer, attached to it. These sensors are used to track the exact movement and position of the hand and fingers while the user communicates with the sign language. This data from the sensors is fed to the machine learning model on our smartphone over bluetooth which converts the gestures into respective speech corresponding to the gesture performed. 




Implementation 
Considering all the hand signs in sign language, we have decided on using 3 flex sensors attached along the thumb, index, and middle finger and an accelerometer on the rear part of the hand. For feasibility, the sensors will be attached to a comfortable glove that can be worn and removed with ease. The physical process of attaching the sensors is completed. The data is also being obtained from all the sensors successfully and is transferred to the system(laptop). The transfer of data is currently done through serial communication and is successful. Nevertheless, we are trying to transfer the data through Bluetooth communication to make the device wireless. Considering our requirement of obtaining the position of the hand, where the data might vary slightly each time even if the same hand signs are used, we have considered using the Support Vector Machine(SVM) algorithm. Presently the algorithm provides satisfactory results with 85 to 95 percent accuracy. As of now the device has been trained with limited gestures and further goals are to be reached.





Value Proposition & Competitive Analysis
The direct customers will be the speech impaired society. Hospitals and medical instrument outlets will be our secondary target. 

At present there are no primary competitors in the market. Such devices are in the prototype phase and are yet to evolve to reach the market. 

The thing that makes us unique is that, the device makes use of basic electronics which brings the product in affordable range, and also makes a great impact to the user’s lives. 


Conclusion and Future Scope

looking for many more amendments that can be brought to the project, like the bluetooth connectivity or using a powerful Microprocessor like raspberry pi which is much stronger and powerful and makes the device stand alone.
Since the device is in it's prototype phase we are focusing more on its functionality rather than the comfort, as the comfort and the finishing will be a part of its manufacturing phase. We believe this revolutionary idea will help society immensely.




