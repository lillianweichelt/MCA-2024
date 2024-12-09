# MCA 2024 Lillian Weichelt
## Week 1
Title: Dawn, Project: Pride and Prejudice, Composer: Dario Marianelli, Time Period: 2005

There are quite a few struggles with working with music. One main one is if your selected pieces are not in the public domain. This makes it almost inaccessible and causes one to look either for free transcriptions or scans. The issue with transcriptions is that it may not always be accurate. Even if the score is easily accessible, the composer could be using unfamiliar techniques that a program like Cusescore cannot understand or reproduce.

The musical score I have found for my theme is a somewhat poor scan of a piano book for the Pride and Prejudice soundtrack. There are shadows and some measures have been slightly cut off. With some musical knowledge, listening to the audio recordings and looking at the metadata will fill these gaps. As a simple example, the name of the composer in the musical score was cut off, so I looked at my metadata and was able to fill in this information.

## Week 2
### Task: Identifying a piece of music related to my theme, then downloading it into Musescore and making corrections regarding rhythm and pitch.
When converting this piece to Musescore, the program added two extra staves for voice even though it was not included in the original document. The original is just a piano piece. Aside from this, it did not include many things from the original. It ignored the duplets in the top line of measure 3, excluding the last two notes in the measure. In the same measure it also only kept the first two notes in the left hand. It also had an issue interpreting the duple in the left hand in measures 5 and 9, but it includes the correct pitches. More rhythm issues happen in measure two where the dotted quarter E is only notated as a quarter. This also happens to the D in the left hand in measure 8. Pitch issues occur mostly when notes are completely gone such as in measure 7 where it should be a series of eighth notes (e, c, e, g, b, c) and is instead five quarter notes that consist of only the first five notes of the measure. This also happens in measure 11 when instead of being written as three eighth notes (e, g#, e) it is written as just a quarter E. A rest is also not included in measure 8. Other than pitch and rhythm, the system notes, some ties, the title, and the composer are not included.

Compare the original and edited versions of the piece here:

<img title="a title" alt="Alt text" src="data/DawnOriginal.jpg">
<img title="a title" alt="Alt text" src="data/DawnFixed.jpg">




## Week 3
### Task 1: Exporting my score which was created last week to MusicXML and MEI.
Access the exported MusicXML and MEI files here:

[MusicXML](/data/DawnTranscription.musicxml)

[MEI](/data/DawnTranscription.mei)

### Task 2: Rendering the MEI file using Verovio in GitHub.
Here is a screenshot of my rendered MEI file in Verovio:

<img title="a title" alt="Alt text" src="data/Verovioweek3.png">

## Week 4
### Task 1: Generating a jSymbolic analysis of the piece, selecting range, mean pitch, most common pitch class, last pitch, and most common rhythmic value.

#### Here are the results:
Range: 41

Mean Pitch: 70

Most Common Pitch Class: 4

Last Pitch: 84

Most Common Rhythmic Value: 0.5

### Task 2: Using the Python notebook on the Moodle to generate a piano roll, scatter plot, and pitch histogram of my piece using music21. 

#### Piano Roll:
<img title="a title" alt="Alt text" src="data/week4pianoroll.png">


#### Scatter Plot:
<img title="a title" alt="Alt text" src="data/week4scatter plot1.png">

#### Pitch Histogram:
<img title="a title" alt="Alt text" src="data/week4histogram.png">

## Week 5
### Task 1: Creating a metadata schema of at least 5 elements, including title, artist, publisher, and at least two others of my choice. 
Here are my choices of metadata and what exactly they provide information for:

#### Title: 
The name of the piece.

#### Artist: 
Depending on the piece, who wrote and/or performed the music.

#### Publisher:
Who or what company the piece of music is published by.

#### Subtitle:
Additional information about the piece, usually provided by the composer or an editor.

#### Date:
The specific date the piece was either written or published.

### Task 2: Modifying the MEI document according to the schema that has been created.

Updated MEI document (as of week 7):


## Week 7
Task 1: Create a second version of your MEI file with the updated metadata, creating genre specifications and licensing data.
Task 2: Rendering the revised MEI metadata along with the score on an HTML page.

## Week 8
Task 1: Identifying and downloading 3 music tracks relating to my theme which are different in their sound and style to my original track and identifying and listing (in a table) the most important technical and non-technical metadata associated with each track. This metadata will include: Title, artist, composer, copyright info, genre, source, file/audio format, number of channels, sample rate, bits per second, and duration.
Task 2: Performing a basic analysis of my 3 tracks in SonicVisualizer by generating a spectrogram. 

## Week 9
Task 1: Extracting features of the 3 tracks by generating a spectrogram, a Mel Frequency Cepstral Coefficients, and a Chromagram.
Task 2: Computing and visualizing the raw features with histograms inside of Python.

## Week 10
Task 1: Generating a similarity matrix using the CSV files from the 3 tracks.
Task 2: Transcribing the original track by converting the WAV file to MIDI using sonic visualizer.









