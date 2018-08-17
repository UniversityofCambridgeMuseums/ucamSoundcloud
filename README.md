# Archive of University of Cambridge Soundcloud Broadcasts

This repository contains downloads for archiving purposes of the University of Cambridge Museums Soundcloud channel.

## Replicating how to get these

To download these files is quite simple and uses the Soundscrape archive. On OSX do the following:

    mkdir ucamSoundcloud
    cd ucamSoundcloud
    mkdir broadcasts
    cd broadcasts

I assume you have python and pip installed.

    pip install soundscrape
    soundscrape univ-of-cambridge-museums
    
After running the last command, you'll see the data download and your broadcast folder should fill up with mp3 files. 

## License

The content is available under CC-BY-NC-SA license at the moment. This may change in future. 
