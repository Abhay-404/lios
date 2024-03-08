Linux-intelligent-ocr-solution
======


Lios is a free and open source software for converting print in to text using either scanner or a camera, It can also produce text out of scanned images from other sources such as Pdf, Image, Folder containing Images or screenshot. Program is given total accessibility for visually impaired. Lios is written in python3, and we release it under GPL-3 license. There are great many possibilities for this program, Feedback is the key to it, Expecting your feedback.

Features
======

1. Import images from Scanner, PDFs, Folder, or Webcam,
2. Take and Recognize Screenshot,
3. Recognize Selected Areas(Rectangle selection),
4. Support two OCR Engines (Cuneiform,Tesseract),
5. Text-Cleaner - Post process your output with match-replace dialog,
6. Full Auto Rotation for any Language(If aspell installed for the language, Eg : "sudo apt-get install aspell-hi" for Hindi,
7. Side by side view of image and output
8. Advanced Scanner Brightness optimizer,
9. Text Reader for low vision with Highlighting, With user selected Color, Font, and Background Color,
10. Audio converter(espeak),
11. Spell-checker(aspell),
12. Export as pdf (text/images),
13. Dictionary Support for English(Artha)
14. Options for save, load and reset settings,
15. Other options - Find, Find-and-Replace, Go-To-Page, Go-To-Line, Append file, Punch File,
Selection of starting page number, page numbering mode and number of pages to scan,
Selection of Scan area, brightness, resolution and time between repeated scanning,
Output Insert position, image rotation and zoom options, etc


Installing
======

>First, install the below dependencies:
```Bash
sudo apt install python3 python3-sane python3-speechd python3-gi-cairo tesseract-ocr imagemagick cuneiform espeak poppler-utils python3-enchant libgtk-3-dev
aspell-en gir1.2-gst-plugins-base-1.0 gir1.2-gstreamer-1.0 
```

```
git clone https://github.com/zendalona/lios.git
cd lios
python3 setup.py install --install-data=/usr
```

Following the third step for a system-wide installation is not necessary. You
can use the following commands instead, as long as you have all the dependecies
installed. This will be useful if you are a Lios developer.

```
export PYTHONPATH=.
bin/lios --datadir 'share/lios'
```

Links
======
Forum : https://groups.google.com/forum/#!forum/lios

Home Page : http://zendalona.com/lios/


Disclaimer
======
    Copyright (c) 2011-2015 Lios Development Team 

    All rights reserved . Redistribution and use in source and binary forms, with or without modification,
    
    are permitted provided that the following conditions are met: 

    Redistributions of source code must retain the below copyright notice, 

    this list of conditions and the following disclaimer. 

    Redistributions in binary form must reproduce the below copyright notice, 

    this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. 

    Neither the name of the nor the Lios team names of its 

    contributors may be used to endorse or promote products derived from this software without specific prior written permission. 

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
    INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
    IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY,
    OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA,
    OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
    OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
    EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE." 

FREE SOFTWARE FREE SOCIETY
