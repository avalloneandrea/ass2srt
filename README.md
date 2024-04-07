# ass2srt

#### Synopsis

ass2srt [-p path] [-l language] [-v verbose]

#### Description

Extract *.ass* subtitles from *.mkv* files and convert to *.srt* format.
Skip the file when a subtitles file already exists or when no subtitles track is found. 

**-p**    
The path to process. Could be a single file or a directory.
Default to the working directory.

**-l**    
The language of the track to extract.
Default to the first subtitles track found.

**-v**    
Explain what is being done.

#### Installation

```
sudo apt install jq
sudo curl https://raw.githubusercontent.com/avalloneandrea/ass2srt/main/ass2srt -o ~/Downloads/ass2srt
sudo install ~/Downloads/ass2srt /usr/local/sbin
sudo rm ~/Downloads/ass2srt
```

#### Examples

```
ass2srt -l ita
```
