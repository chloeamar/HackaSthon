# HackaSthon

Dear students from ENSAE, CentraleSupelec and Mines de Paris, first and foremost welcome to Israel !!! We are very glad to have you here and hope that you will enjoy your trip and this particular day. 

The goal of this Hackathon is to do hand-to-mouth detection using Machine Learning. More specifically, you will have to detect if someone is driking thanks to a smartwatch we built using a ST accelerometer. 

This is a competition but we do not expect neither you to build an AI algorithm from scratch nor to do boring stuffs. We only want you to have fun and to see how your skills can be applied in a company such as STMicroelectronics. Moreover, we decided to challenge you by asking some opened questions. There is no bad answer and we really encourage you to think completely out of the box. Be Israeli !

Since the skills of the 3 schools are different and the level between students is heterogeneous, we will ask you both technical and qualitative questions. 

Do not hestitate to ask questions ! For the coding part, we strongly recommend you to use Google Colab.

Once you have finished, please send me your results (ppt, notebook, .py,...) at daniel.amar@st.com. 


# 1st Step : Using the Board

## Building the smartwatch!


First, try to build the smartwatch and tie it to one of your wrists.

Be careful, orientation matters. It should be done like below.

![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/image001.jpg?raw=true)



![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/image002.jpg?raw=true)


Then, try to connect it to your computer using the cable. Once, it is connected, you should install in the Mass Storage either the file IIS3DWB_SDCard_L432.bin or either the file IIS3DWB_SDCard_L412.bin given the board you are using (it is written on the board, for instance you should use L432 for the example here). 


Once this is done. It should blink like this:


![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/Ready.gif?raw=true)




Then, you can start registering your own data. To do that, you need to push the button during approximatively 2 seconds. Once this is done, you have 2 seconds before it starts to record your movements during 4 seconds. When it records, the LED should blink like this:

![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/Recording.gif?raw=true)


Then, remove gently the SD card and put it in the usb port. You should be able to read your data. Be careful when you save your data and try to divide them into a "Drink" folder and a "Normal" one ("Normal" stands for not drinking samples).



## Technical Questions


1. First, let's play with the smartwatch ! Please, try to collect 10-20 samples (5-10 samples when your drink and 5-10 samples when you don`t drink). In the meantime, the other members of the team can access the github folder **Input** where we add samples we created for the challenge.


2. Plot in 3D some of the samples you generated. Is the signal noisy ? Why ? Try to make it much more readable. 

3. In the Input folder, we have around 120 samples : 60 positive samples (drink) and 60 negative samples (not drinking). According to you, what will be the main difficulties regarding the classification we want to make.
Bonus: Provide 2 ways to improve already classification

4. Create a Train datasets and one Test dataset. 
For simplicity, normalize your data. Be careful, you should calculte mean and std only on the train dataset.

5. Use a stastical or Machine learning approach to classify 

6. In the notebook, we implemented a very basic LSTM model which is often used for time series. Make it run. 
 
7. We made a 55%-60\% prediction which barely outperformed the random threshold of 50\% (check it). Try to improve it as much as you can. If you don't have time, try to suggest ideas.  

## Qualitative Questions

Imagine and draw a smartwatch for this specific application. According to you, in which concrete applications detecting if someone is eating/drinking can be very useful ? Try to argumentate this and don't hesitate to put some drawings. 


## Opened and Bonus Questions

If you have reached this part, congratulations ! We will now talk about opened questions. Be as inventive as you can, there is no bad answer. For these questions do not hesitate to reach Gidi Mizrahi. 

1. ST is working a lot with MEMS. To make it very short, MEMS are sensors and they are composed of Microphone, Gyrometer, Accelerometer, Pressure & Temperature sensors, Magnetometer. What is the next MEMS ? 

2. How can we improve MEMS ?

3. Imagine a new applications/technology in which you could use data from movements measured by MEMS. 































