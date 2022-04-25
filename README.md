# HackaSthon

Dear students from ENSAE, CentraleSupelec and Mines de Paris, first and foremost welcome to Israel !!! We are very glad to have you here and hope that you will enjoy your trip and this particular day. 

The goal of this Hackathon is to do hand-to-mouth detection using Machine Learning or Deep Learning. More specifically, you will have to detect if someone is driking thanks to a smartwatch we built using an accelerometer. 

This is a competition but we do not expect neither you to build an AI algorithm from scratch nor to do boring stuffs. We only want you to have fun and to see how your skills can be applied in a company such as STMicroelectronics. Moreover, we decided to challenge you by asking some opened questions. There is no bad answer and we really encourage you to think completely out of the box. Be Israeli !

Since the competencies of the 3 schools are different and the level between students is heterogeneous, we will ask you both technical and qualitative questions (we do not have the answers for some of them...). \\

The topic of the challenge will be hand-to-mouth detection using Machine Learning orDeep Learning. We tried in this Hackathon to make things as simple as possible since most of the students have never studied DL. Again, do not hestitate to ask questions !


# 1st Step : Using the Board

## Building the smartwatch!


First, try to build the smartwatch and tie it to one of yours wrists.

Be careful, orientation matters. It should be done like below.

![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/image001.jpg?raw=true)



![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/image002.jpg?raw=true)


Then, try to connect it to your computer using the cables. Once, it is connected, you should install in the Mass Storage either the file IIS3DWB_SDCard_L432.bin or either the file IIS3DWB_SDCard_L412.bin given the board you are using (it is written on the board, for instance you should use L432 for the example here). 


Once this is done. It should be like this:


![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/Ready.gif?raw=true)




Then, you can start registering your own data. To do that, you need to push the button during approximatively 2 seconds. Once this is done you have 2 seconds before it starts to record your movements during 4 seconds. When it records, the LED should blink like this:

![alt text](https://github.com/danielAmar02/HackaSthon/blob/main/Recording.gif?raw=true)


Be careful, when you save your data try to divide them into a "Drink" folder and a "Normal" ones ("Norma" stands for not drinking samples).



# Questions

\begin{enumerate}
    \item First, let's play with the smartwatch ! Please, try to collect 20 samples (10 samples when your drink and 10 samples when you don`t drink). In the meantime, the other members of the team can access on the githublink the samples we created for the challenge.
    \item Plot in 3D some of the samples you generated ? Is the signal noisy ? Why ? Try to make it much more readable. 
    \item Counting your samples, we have around 120 samples : 60 positive samples (drink) and 60 negative samples (not drinking). According to you, what will be the main difficulties regarding the classification we want to make.
    \textit{Bonus: Provide 2 ways to improve already classification}
    \item Create a Train datasets and one Test datase
    \item Use a stastical or Machine learning ways in order to classify 
    \item In the  github file, we implemented a very basic LSTM model which is often used for time series. We made a 60\% prediction and thus outperformed the random threshold of 50\%. Try to improve it as much as you can (hyperparameter optimization, using much more complicated models, using stratified K-fold cross validation,...).  

\end{enumerate}
































