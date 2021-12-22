# Analyzing-Piano-Recordings-Using-FFTs

Final Project: Analyzing Piano Recordings Using FFTs

My code requires the following modules: pyaudio, wave, time, display

It also requires adjusting the notebook settings. I just put the following the terminal: jupyter notebook --NotebookApp.iopub_data_rate_limit=1e10

The goal of this project is to use FFT to determine the notes that are played by a piano in recordings pulled from the internet. Three mp3 files were found and converted into wav files. Several modules were installed to be able to run the program. The first audio file is a very clean C-major scale with no noticeable noise and no chords. The second audio file is a recording with some significant noise. The recording is three distinct notes followed by a chord made up of those three notes. The last audio file is a C-major scale with chords. There are actually two octaves that alternate in the scale.

Part one:

Read in the audio file of the first C-major scale  
Use FFT to find the frequency of the notes.  
Use the frequencies found in objective 2 to create a new audio file of the scale.  
Play the new audio file from objective 3 and the original audio file to see if there is a noticeable  difference in sound.  
Look up the frequencies of the notes in a C-major scale and use them to create another audio file.  
Play the audio file from objective 5 and objective 3 to see if the piano was decently tuned.  
Part two:

Read in the audio file of the triad construction.  
Use FFT to find the frequency of the notes and the noise.  
Identify the three notes when they are played individually.  
Identify the three notes that are played in the chord.
Construct a new recording.
Part three:

Read in the audio file for the second C major Scale
Use FFT to find the frequencies that have the highest amplitude.
Future additions to the project:

I know there is a way to dissect a chord and get the notes, but I could not figure it out or find an example online. I would work more on this problem if I had more time.
I started out trying to animate the audio files, but jupyter notebook did not support animation modules. I found that you can get modules that animate plots like a movie, but I did not have enough time to implement it.
It would be cool to work with a recording of two different instruments at the same time.
