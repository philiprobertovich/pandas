# Pandas-Spotify Artists, Tracks, Albums Dataframes

### By Philip Kendall

#### This project utilizes three datasets for Spotify Artists, Tracks, and Albums. Profiling, join methods, map transformations, and aggregate functions are used to analyze these datasets.

## Technologies Used

* Python
* Pandas
* Git

## Description

The datasets are imported and profiled using the head, tail, and shape methods and attribute. .loc method is used to output lines 10-20 of albums dataframe.The datasets are then normalized and cleaned by filling null values, removing cluttered columns, and removing duplicates. A transformation map is created to swap out an empty list for a null value within the genres column in the artists dataframe. The lyrics column is dropped in the tracks dataframe. Two merged dataframes are created. One with the artists and albums dataframe, and the other with the albums and tracks dataframes. Aggregate functions are applied to the artists dataframe to find out different statistical information, such as the frequency an artist appears in the dataframe, and the most popular artist.

## Setup/Installation Requirements

* Fork over the the repository to your own Github account.
* Clone your Github repo down to your local machine and into the directory you would like this project to be stored.
* Navigate to the main.py file and open it in your text editor.
* At the same time, in a terminal window, install the requirements.txt file by typing pip install -r requirements.txt on the command line.
* After that, the application should be able to run.
* To get the Spotify datasets, type in the following command into your command line: bash gsutil -m cp gs://data.datastack.academy/spotify/*csv .

## Known Bugs

N/A

## License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The below copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2022 Philip Kendall