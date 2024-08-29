# `digital-music`

There are a few Python tools and libraries that can help with digitising scanned music scores and converting them to playable digital formats:

## Optical Music Recognition (OMR)

For converting scanned sheet music images to digital formats:

- **SheetVision**: An open-source Python library for optical music recognition. It can detect musical elements in scanned scores and output to MIDI format[5].

- **Audiveris**: An open-source OMR system written in Java, but with Python bindings available. It can convert scanned scores to MusicXML format.

## Digital Music Formats

Once you have the music in a digital format, you can work with it using:

- **Music21**: A powerful Python toolkit for computer-aided musicology. It can parse, analyze, and manipulate symbolic music data in various formats like MusicXML and MIDI[2].

- **Abjad**: A Python API for formalized score control. It allows you to build up complex music notation programmatically[2].

- **LilyPond**: While not Python-specific, LilyPond is a music engraving program that uses a text-based input format. Python can be used to generate LilyPond files[4].

## Audio Playback

To play back the digitised music:

- **FluidSynth**: A software synthesiser that can render MIDI files to audio. Python bindings are available.

- **pygame**: Has MIDI playback capabilities and can be used for simple audio output.

## Integrated Solutions

Some projects aim to provide end-to-end solutions:

- **cadenCV**: An optical music recognition system written in Python that can read sheet music and sequence a MIDI file for playback[6].

- **music-sheet-digitisation**: A project aiming to digitise music sheets into playable audio files using Python and AI techniques[1].

While there isn't a single comprehensive solution, combining these tools can allow you to go from scanned images to digital notation and audio playback. The process typically involves:

1. Using OMR to convert scans to a digital format (e.g., MusicXML or MIDI)
2. Processing and manipulating the digital score with libraries like Music21
3. Rendering the score to notation (e.g., with LilyPond) or audio (e.g., with FluidSynth)

OMR technology is still evolving, and manual correction may be needed for complex scores. 

The accuracy of the digitisation will depend on the quality of the original scans and the complexity of the music notation.

References:

- [1] https://github.com/weberjo8/music-sheet-digitization
- [2] https://wiki.python.org/moin/PythonInMusic
- [3] https://blogs.cul.columbia.edu/dcip/2016/12/22/digital-archives-and-music-scores-analysis-manipulation-and-display/
- [4] https://stackoverflow.com/questions/5411185/sheet-music-library
- [5] https://www.reddit.com/r/learnpython/comments/ou69pu/are_there_any_python_libraries_that_read_sheet/
- [6] https://github.com/afikanyati/cadenCV
- [7] https://av.tib.eu/media/21107
[8] https://www.youtube.com/watch?v=9boJ-Ai6QFM
