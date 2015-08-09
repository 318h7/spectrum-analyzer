## Synopsis

spectrum-analyzer is a real-time microphone Spectrum Analyzer written in python using pyqtgraph for real-time plotting and pyaudio for gathering microphone data.

## Usage

```{r, engine='bash', count_lines}
$ python sa.py
```

The GUI - user can scroll around.

 ![screenshot of the program](https://github.com/sbarratt/spectrum-analyzer/raw/master/demo.png "Screenshot of the Program")

## Installation

```{r, engine='bash', count_lines}
$ git clone https://github.com/sbarratt/spectrum-analyzer.git
```

Dependencies:
numpy (pip install numpy)

pyaudio (pip install pyaudio)

pyqtgraph (pip install pyqtgraph)

## License

The MIT License (MIT)

Copyright (c) 2015 Shane Barratt

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
