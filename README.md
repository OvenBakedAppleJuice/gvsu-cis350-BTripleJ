##Team Name: B Triple J
# Description:
This project is an audio visualizer application. It has two major components, a GUI that allows a user to select audio input from a variety of sources (including a microphone and MP3 file) and an arduino that creates a display on an LED matrix. The arduino communicates with the application over USB and the USB device can be selected in the GUI along with the desired color of the audio visualization. Some audio visualization happens in the GUI as well.

# Team Members and Roles
* [Josh Dobbs](https://github.com/OvenBakedAppleJuice/CIS350-HW2-DOBBS) (GitHub Manager, GUI Developer)
* [Jason Gray-Moore](https://github.com/graymooj/CIS350-HW2-Gray-Moore.git) (Tester, Communications Manager)
* Joeseph Shotts (Software Developer, Arduino Tester)
* Blake Collins (Software Developer, Arduino Tester)

# Prerequisites
## Python
* If you are using the executable, you just need to ensure the executable is in the same folder as “ffmpeg.exe” and “ffprobe.exe”. Those two binaries are needed for the MP3 file player, but not for the audio microphone input. You can find the executable in the “python_work/_Other/Build Exe” folder.
*If you are not using the executables you will need to install a number of python libraries and python itself. You can find a list of python libraries in “python_work/_Other/PythonLibraries.txt”. You will then need to run the script “main.py” in the python_work folder.
*The actual usage of the GUI should be self explanatory. It is intended to work with an arduino to create a LED display. The GUI itself does do a limited audio display as well.
*The GUI can only support one audio input at a time, either from a MIC (or other system audio device) or from an MP3 file selected on the computer.

## Arduino
* Ensure you have an arduino uno and LED matrix (similar to this: [link](https://www.amazon.com/BTF-LIGHTING-Individual-Addressable-Flexible-Controllers/dp/B088BTYJH6/ref=sr_1_1_sspa?crid=4E283SSEU9YM&dib=eyJ2IjoiMSJ9.QIxsq20ln0JI94AkasvER9RyY8WzgNHyyVYpe4ihuTYvE-mm0Da8Od4sWxkpIkO6dtInImTRd7fNRfWf6cWslRbozawxuo8Eot4iJyvNpDQAsu3_LiqlLG5TOUWl6KP2Im81xkp_YBotkEtTRhVBOnRgBuvgfSYRnwAqT5VvQfQNxqCNx_XtZ9JSSaLCi6m1D_zTVguZnA5XAT1cy2Rw12Yr-Ahb7wuxKdUiQDMFKYSw-J_ir7RhHv6DiWq7BdFO1iHySROeAuAbet2puRDUV4iH1SVUXO3wEHA0TxH1MgE.DVMcUWklAz5J1zzSYGVSLyh-CnxyULD6Ghe4_gO1dpM&dib_tag=se&keywords=LED%2Bmatrix%2B16x16&qid=1750205034&sprefix=led%2Bmatrix%2B16x16%2Caps%2C137&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1))
* Connect the VCC pin on the LED matrix to the 5V from power supply
* Connect the GND pin on the LED matrix to the GND pin on the Arduino
* Connect the DATA IN pin of the LED matrix to digital pin 6 on the Arduino
* Install the FastLED arduino library.
* Install the arduino program on the arduino using the arduino ide.
* Plug the Arduino into your computer using the USB cable

# Run Instructions
* Open the AudioViz Application
* Launch App and select the port for Arduino on the USB Port tab
* Select your Audio Device for microphone input or Audio MP3 file
* Press start or start and the data will transfer to the Arduino and the histogram will update
* Choose between Amplitude more and Frequency mode to transfer different data to the Arduino



