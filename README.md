# Lock_in_phase_extraction

A piece of  Wolfram code implementing lock-in measurement that utilise build-in audio input &amp; output channels of the PC


Working principle is as follows;

1) Generating numerical data based on Sin() with given frequency and duration.

2) Converting the data to Audio with a given sample rate.

3) Creating two audio streams; one for playing the generated signal, and the other for recording using microphone input.

4) Once the process started, phase between these two signal is dynamically calculated and plotted in real time.

To test the result, one can basically connect the headphone out to the mic-in via standard aux cable as the phase should be very low (< 1 Degree) in such case.

\nAmplitude difference where the phase is near zero should result in lock-in voltage approximately, if it is correctly callibrated. 

Do not expect perfect result as this is just a basic demonstration of the phenomenon and the goal is to make possible to play with it based on just a regular pc with sound card.
