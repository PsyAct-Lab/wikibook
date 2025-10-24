
# How to Process Pupil Data from EDF using Data-Viewer

## Step-by-step 
0.	**Go to Hiddai’s current computer**
1.	**Open an EDF file**
    •	Choose the subject’s EDF file (saved probably in google drive/Other computers/New Experiments Computer/your_project/subject’s folder)
    •	View → Trial Viewer to sanity-check that samples and messages look normal (should be open automatically)
2.	**Open the Sample Report (top left corner)**
    •	Analysis → Reports → Sample Report…
3.	**Choose relevant Variables/columns e.g.**
    TRIAL_INDEX
    LEFT_IN_BLINK 
    LEFT_PUPIL_SIZE
    RIGHT_IN_BLINK
    RIGHT_PUPIL_SIZE
    SAMPLE_MESSAGE
    TIMESTAMP
4.	**Re-sample**
    •	it to e.g. 100Hz (last check box in the window)
5.	**Export**
    •	Click Next, Save the folder under whatever in your subject’s folder (and/or where you gather the data) 
    •	Then a save window pops up after creating the directory with the folder output
    •	Choose a relevant/correct name: e.g. pupil_data_100hz.txt (this is the relvant file)
    •	Then save
8.**Reorder (optional)**
    •	I, for example, didn’t need the rest so you can extract the relevant file, save it where you need it and delete the rest
6.	**Quality check**
    •	Open the file and check if it looks correct e.g. (pic below or check effort_anticipation_task/subject for example)

![data example image](https://osf.io/download/ytuka)
    **Common gotchas to look out for** 
    •	Timestamps look like time-since-trial
    •	Only one eye or no blink flags → Reopen Columns and add the missing eye/flag fields.
    •	No messages 

