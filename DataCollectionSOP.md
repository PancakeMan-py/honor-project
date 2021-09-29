## 1.Device provided
redmi phone, respeck

## 2.Sensor placement

Respeck
Everyone will need to wear the sensors in the same places to ensure consistency across the data.

The Respeck sensor should be placed on the left lower ribcage, with the blue half against the skin. Make sure that the Respeck is first put into the small plastic bag provided. You should be able to read the Respeck label when placing it on your chest – this ensures the sensor is held the right way up, as shown in the figure below.

Secure the sensor to the chest using the MeFix tape provided. If you run out of tape you should let us know and we will provide you with more.
![image](https://user-images.githubusercontent.com/70093036/135271305-58338f79-314a-4d47-b594-b5fec103501f.png)

## 3.Connection to sensors
Open the PDIoT app on your phone and navigate to the Record Data activity. Make sure both sensors are connected to the app by verifying that the live data at the bottom of the screen is changing.

Respeck:

Green light blink -> sensor ON and NOT CONNECTED
Blue light -> sensor ON and CONNECTED
Red light -> sensor ON and DISCONNECTED
## 4.Recording activities
Finally, you can record data in the Record Data activity. Choose the appropriate Sensor type and Activity and please use the university student number as the subject ID. You can enter any additional notes you have about the upcoming recording.

You will be able to verify that your sensors are running as expected by watching the Live Data fields at the bottom of the screen.

![image](https://user-images.githubusercontent.com/70093036/135271653-8d20eecf-0321-4228-9571-465492bd304a.png)
Hit Start Recording when you are all set up. When you are done with a recording, hit Stop Recording. If something goes wrong during the recording you can cancel it by pressing the Cancel Recording button.



## 5.Activity descriptions


Please record each activity for 30 seconds!

You are required to ensure the recording only contains one activity. For example, if you start recording data for walking and you only start moving after the first 3 seconds, you should trim the first 3 seconds of this recording, as they are not representative of the walking activity. The total length of your recordings AFTER TRIMMING should be 30 seconds.

If you accidentally collect less data for one activity please redo the recording.


Walking
Find a space where you can walk in a straight line for 100 steps or take as few sudden turns as possible. Walk at a normal pace and try to not stop during the recording.

Running or Jogging
Find a space where you can run or jog in a straight line for 100 steps or take as few sudden turns as possible. Try to not stop during the recording.

Ascending stairs
Find a space where you can continuously climb a flight of stairs for 100 steps, for example Appleton Tower. Walk up the stairs at a normal pace and do not stop for the 30 seconds of the recording.

Descending stairs
Find a space where you can continuously descend a flight of stairs for 100 steps, for example Appleton Tower. Walk down the stairs at a normal pace and do not stop for the 30 seconds of the recording.

Shuffle walking 
Find a space where you can walk slowly in a straight line for 100 steps or take as few sudden turns as possible. Walking in differernt patterns, example can be found in https://www.youtube.com/watch?v=k-Tk2rZfbyc

## 6. Obtaining the recorded files

Check data collection result.

Files are saved on the phone’s internal memory as csv files, on the path: Android > app > data > com.specknet.pdiotapp > files > Filename.csv

You can access these files either by:

connecting your phone to a computer via USB and checking the internal memory, or
navigating to this folder from a file browser app on your phone and send them via Bluetooth, email, message etc.
Depending on which Android version you are running, you might need additional apps rather than the pre-installed ones to get to these files. From Android version 11, you should use apps like Total Commander to view hidden system files. Any Android version lower than 11 will allow you to see these files in a normal file browser on your phone.

The filename is formatted as follows: {sensorType}_{studentID}_{activityType}_{timestamp}.csv

This should ensure that each file has a unique name among all students.

If you are using a Redmi phone provided by us and you need to obtain the files via USB you might need to restart the phone to see the new files appear in the file browser on your computer.
