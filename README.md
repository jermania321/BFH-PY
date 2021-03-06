![BFH Banner](https://trello-attachments.s3.amazonaws.com/542e9c6316504d5797afbfb9/542e9c6316504d5797afbfc1/39dee8d993841943b5723510ce663233/Frame_19.png)
# AudioViz
Audio Viz is the newest  completely open source, user friendly music visualizer website that allows any user to upload an audio of their liking and get back a video with the most stunning of visuals reacting to the various features of music. Due to the diverse nature of the website, it also allows the users to download the full video entirely for free . We thank you for joining us on our journey to make music into not just an audio experience, but into a full audio video experience like none other before.

https://audio-vizz.herokuapp.com/main
## Team members
1. Sidharth M S [Github link](https://github.com/sidharth980)
2. Jerry Zachariah Jose [Github link](https://github.com/jermania321)
3. Rahul. V [Github link](http://github.com/rzinc)
## Team Id
BFH/recZxreJLMNOtvhse/2021
## Link to product walkthrough
https://www.loom.com/share/3d5e92baf9be474d804a489939544c43
## How it Works ?

When the user first loads the website, they are greeted with a log in/sign up screen.
![image](https://user-images.githubusercontent.com/33323329/119361166-fda71a00-bcc8-11eb-8df1-aef95143f722.png)

Existing users can sign in with their email and password, however new users must create an account before proceeding.

Once the user is logged in, they are greeted with the conversion page.
![image](https://user-images.githubusercontent.com/33323329/119361817-b3726880-bcc9-11eb-8db2-d72b9913a3cf.png)

Here, the user uploads the their desired music file(less than 5MB due to current server resource limitations) and presses the upload button.

Once the file is uploaded(speed may vary depending on your internet connection), the user will be taken to the convert page where they must press the convert button to start the conversion process.

![image](https://user-images.githubusercontent.com/33323329/119362846-c8033080-bcca-11eb-8070-7c67692b218a.png)


The conversion process will now begin and we must simply wait for the computer  to do it's analytical magic.
![convert2](https://user-images.githubusercontent.com/33323329/119363337-537cc180-bccb-11eb-81e4-1bece7942a21.PNG)


Once the conversion is complete, an option to donwload the video will show up, clicking on which downloads an mp4 file which the user can play whenever they want.
![image](https://user-images.githubusercontent.com/33323329/119375111-09e6a380-bcd8-11eb-81d6-fe4355eeca99.png)

Visit the site to try it yourself! (https://audio-vizz.herokuapp.com/main)

## Libraries used
librosa - 0.8.0,
Flask_SQLAlchemy - 2.5.1,
Werkzeug - 1.0.0,
opencv_python - 4.5.2.52,
ffmpeg_python - 0.2.0,
Flask - 1.1.1,
numpy - 1.19.5,
gunicorn
## How to configure
Install the python libraries uses(can be done using pip install).
Ensure the ffmpeg software is installed on the system.
## How to Run
Open a terminal to the downloaded project folder and run app.py by typing `python app.py` into the terminal and pressing enter.
Go to the server link to visit the webpage
Control clicking the localhost link from the terminal should also work
(while running via the site  depending on the size and complexity of the audio file the time to convert the file to the video format might take more time..)
