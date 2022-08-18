# Brain Wave Detection System 

Project is focused on the detection and extraction of a brain wave signal with the help of analog as well as digital circuitry. Using active electrodes on human scalp, the brain signals were fed into a series of hardware and software stages. Simple conscious movements such as blinking caused a change in the detected waveform. Although the project was not successful in discriminating between different motions or utilizes the signal to control an electrical device, the team was able to successfully separate and display the alpha waves after filtering off all associated unwanted signals.

## PROJECT IDEA: -
In this research paper we have designed a new instrument which reads the subject
brain waves continuously and gives feedback in the form of led signal. In previous
protocols, researchers concentrate on only drowsiness but they are not gives
important while driving. Some of them have done this research using real car. But
these protocols feedbacks only after the subject slept. So in order to rectify these
problems we designed new protocol which identifies subject drowsiness before he
is going to sleep.
With the help of this, we are analyzing the brain wave signals. Human brain has
millions of interconnected neurons. The interaction pattern between these neurons
is represented as emotional states and thoughts. This pattern will be changing as the
human thoughts change, which in turn produces different electrical waves.
In the proposed system, an alarm with low power consumption is placed near the
driver which will wake up the driver while he falls asleep during driving. The EEGsensor senses the brain signals of the driver and if he falls asleep it will send the
signal to the embedded system for further processing. The signal is sent to the
amplifier and the amplified signal is given to the comparator that compares the
input signal (amplified brain wave signal) with the threshold voltage that is set
according to different sensation states of the driver.


## WORKING OF PROJECT: -
The proposed works are briefly described in this section. The system hardware
consists of the signal acquisition module. The EEG signal is captured through the
EEG electrode; the inbuilt amplifier will amplify the captured EEG signals. The
EEG signals is then passed to the High Pass Filter which is capable of filtering
60Hz. Then it is given to the Low Pass Filter which is capable of filtering up to
5Hz. At the same time the amplified EEG signals is given to the LM339
comparator, the acquired voltage is compared with the reference voltage. From the
obtained voltage ,the various states of the driver is indicated using LED whereas
the red LED represents the active state of the driver, the yellow indicates the normal
state of the driver and the green represents the drowsy state of the driver. The
program for the whole module is dumped into the microcontroller. Whenever the
drowsy state is detected, the microcontroller enables the motor to slow down and
the drowsy state of the driver is indicated using LCD display and the alarm starts
to ring.Fig.2.1.1, Shows the overall block diagram of the proposed system


![project architecture](https://user-images.githubusercontent.com/91308138/185475871-d17519d7-3edb-4d1a-a667-d9b32bca47b8.PNG)


## EXTRACTION OF BRAIN SIGNAL: -
The electroencephalogram (EEG) is a record of the electric signals generated as
the result of brain activity. EEG provides important and unique information about
the sleeping brain. While EEG signals have advantage in making accurate and
quantitative assessment of alertness levels.EEG signal will be obtained from the
Brain wave Sensor. EEG signal is quite small, ranges from 1Hz to 100Hz and
amplitudes vary from 1µV to 100µV.

![extraction of brain signal](https://user-images.githubusercontent.com/91308138/185476250-a0c89e5c-2edb-49ca-8344-bc5e60bcf0c3.PNG)

<br>

<br>

![eeg signal](https://user-images.githubusercontent.com/91308138/185476367-35819ea7-f2da-45c0-9d89-7a1dbab16adf.PNG)

<br>


<br>

![result simulation](https://user-images.githubusercontent.com/91308138/185476657-f175c696-a08f-4bd9-adac-4266a88f8efd.PNG)

<br>


https://user-images.githubusercontent.com/91308138/185476764-304faf7e-db6f-4937-9696-5ebdafe8c25e.mp4


checkout the synopses , report and ppts for more details.
