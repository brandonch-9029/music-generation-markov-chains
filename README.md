# Markov Chain Music Generation

1. File Description
- cxwn84_report.pdf: 1000 word report
- cxwn84_video.mp4: 3 minute video demonstration
- cxwn84_evaluation_data.xlsx: Spreadsheet containing results and chart figures for Blind Listening Test and Entropy evaluations
- cxwn84_code.zip: 
    - main.ipynb: Jupyter Notebook containing all my code
    - CoCoPops-main: Dataset
    - pickles: Pickle files containing the Python Counter dictionary objects of all the pitch and quarterLength counts
    - csv: Comma-separated values containing the note and duration transition tables for the 214 song bigrams
    - Evaluation: The MIDI files used in the Blind Listening Test
    - basic.midi, inter.midi, adv.midi: Typical examples of music output for my system

2. Code Requirements
- Python Standard Library Modules: random, os, pickle, collections, typing, and fractions.
- Additional Modules:
    - numpy
    - music21
    - muprocdurham 

3. Listening to MIDI files on VLC Media Player
- For VLC to play a MIDI file, it needs a SoundFont file (extension .sf2)
- In my video demonstration and blind listening test, I use the SoundFont from: https://www.schristiancollins.com/generaluser.php
- To install a SoundFont file in VLC, you can follow the wiki: https://wiki.videolan.org/Midi/
    - Open Preferences
    - Select Display Mode "All"
    - Input/Codecs > Audio Codecs > FluidSynth
    - Select the .sf2 file with Browse
    - Click Save
    - Play the MIDI file on VLC
