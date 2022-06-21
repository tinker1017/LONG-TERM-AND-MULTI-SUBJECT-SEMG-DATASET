# LONG-TERM-AND-MULTI-SUBJECT-SEMG-DATASET

**Abstract**   
This is a long-term multi-subject sEMG signal dataset, which including confounding factors time lapse and individual difference. The dataset contains one set of static gestures and two sets of dynamic gestures. A total of 13 subjects participated in the experiment that lasted ten days, with the ninth subject dropping out midway, so the dataset only has data from 12 subjects. gForcePro+, a wearable sEMG sensors produced by OYMotion Technologies (Shanghai, China), was used to recorded sEMG signal. It has built-in 8-channel highly sensitive EMG sensor, 9-axis motion sensor, bluetooth BLE4.2 and other modules. The sampling frequency is 1000 Hz. And it has supporting acquisition software to receive and save data via Bluetooth. This dataset stores only EMG signals.

**Gesture**   
The file **'gesture.xlsx'** has images, descriptions, and labels of all gestures. Please download and view.

**Dataset Description**   
Every gesture was repeated ten times. For all gestures, subjects held for 5 seconds, following a rest of 2 seconds. After recording ten repetitions of one gesture, rest for 2 minutes. All three sets of gestures were collected within one session in one day. Each subject was required to participate in ten sessions. The time interval between two sessions must be greater than 24 hours.

**File format**   
All data is stored in '.mat' format. Inside every '.mat' file, EMG signals, subject No., session, gesture type, gesture label and repetition were recorded.   
Keywords explanation：
* emg: The sEMG signals of one gesture, repeated ten times.
* subject: The number of suject.
* session: The day subjects participated in the experiment, ten days in total.
* gesture type: The type of gesture, there are 'static', 'dynamic 1', and 'dynamic 2' types.
* gesture label: Gesture label. Download the file **'gesture.xlsx'** and view the gesture corresponding to the label.
* repetition: A hand gesture repeated ten times.

**How to use**   
1. Download all files and unzip them.
2. We upload the raw sEMG signals, which you can process according to your research needs.
3. File **'subject_information.xlsx'** records the subject's number, basic information and participation in the experiment, download the file to support understanding the naming rules of the file.

Root directory: LONG-TERM-AND-MULTI-SUBJECT-SEMG-DATASET/   

The floder **'static_gestures'** stores static gesture data. The floder **‘dynamic_gestures_1’** stores the first set of dynamic gesture data. The floder **‘dynamic_gestures_2’** stores the second set of dynamic gesture data. Folder name 'Sx' is the subject's number and zip file name 'Tx' is the number of session. After unzipping, file name 'sx_tx_gx.mat' is the sEMG signal of the subject ‘sx’ performing the xth gesture ten times in the x session. For example, ‘s1_t1_g1.mat’ stores the data that the first subject repeated the first gesture ten times in the first session. Detailed information about the subjects and their participation in the experiment is documented in file **'subject_information.xlsx'**. 

