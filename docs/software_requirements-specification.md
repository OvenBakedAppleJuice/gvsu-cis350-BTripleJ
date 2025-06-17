# Overview

This document describes the functional and non-functional requirements of the semester project for BTripleJ in CIS350.

The project is an audio visualizer, using a microcontroller, LED array, along with Python audio processing and a GUI. These functional requirements describe the functionality of the entire system, and the non-functional requirements outline some of the ways it may be implemented.

# Functional Requirements

1. The system shall have a GUI that allows for controlling the audio visualizer.

2. The system shall have a GUI to select a port for Arduino.

3. The system shall have a LED display for the audio visualization.

4. The system shall be able to use audio from a microphone.

5. The system shall be able to use audio from a file.

6. The system shall send serial data to a microcontroller.

7. The system shall parse pitch and volume from serial data.

8. The system shall find the frequencies from a given audio input.

9. The system shall find the amplitude from a given audio input.

10. The system shall have documentation to explain how to use it.

11. The system shall display amplitude of a given audio input.

12. The system shall display frequency of a given audio input.

13. The system shall notify the user if a serial port is unavailable.

14. The system shall power the LED reliably.

15. The system shall allow the user to easily turn on/off the system itself.

16. The system shall display audio values to show proper usage of the sound system.



# Non-Functional Requirements

1. The system may be able to use an arduino microcontroller.

2. The systme may be able to use an esp32 microcontroller.

2. The system may use the FastLED library.

3. The system may use python PyAudio, an API for PortAudio, to get audio input.

4. The system may use the Tkinter library for the GUI.

5. The system may use python multithreading to collect audio while processing it.

6. The system may process data in 200 milliseconds.

7. The system may filter the microcontroller inputs.

8. The system may be able to perform with both Mac and Windows.

9. The system may use prebuilt python packages.

10. The system may have a GUI with minimal buttons.

11. The system may use python numpy to process data quickly.

12. The system may operate continuously without crashing.

13. The system may set a maximum and minimum brightness for the LEDs.

14. The system may be durable for prolonged use.

15. The system may use different color LEDs to denote different frequencies.

16. The system may be modular for future updates.

17. The system documentation may be understandable to someone with no knowledge of the system.

