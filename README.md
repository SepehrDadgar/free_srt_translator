#### hey
i found two other projects that to the same thing but they needed the google cloud API which 
i can't afford 😢 so i made this which uses the free api from the same server that translate.google.com uses

# Free SRT Subtitle Translator

Free SRT Subtitle Translator is a Python script that uses the Google Translate API to translate subtitles in `.srt` format from one language to another. It's designed to be easy to use and works by dividing the subtitles into chunks to translate them more efficiently.

## Features

- Translate entire subtitle files from English to Farsi (Persian) by default.
- The source and target languages can be changed within the `.py` file.
- Splits the subtitle file into smaller pieces to speed up translation.

## Installation

To use Free SRT Subtitle Translator, follow these steps:

1. Install the required Python packages:

```bash
pip install srt numpy googletrans==4.0.0-rc1
```
Clone the repository:
```
git clone https://github.com/SepehrDadgar/free_srt_translator.git
```
Navigate to the script’s directory.
# Usage
To translate an .srt file, run the script from the command line:
```
python srt_translator.py -i "path/to/original.srt" -o "path/to/translated.srt"
```
Make sure to replace path/to/original.srt with the file path of your original subtitle file, and path/to/translated.srt with the desired path for the output file.

Note:
The default source language is English (en), and the target language is Farsi (fa). You can change these within the .py script if needed.
