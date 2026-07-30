# MapReduce Practice

A small collection of Python MapReduce jobs built with [mrjob](https://mrjob.readthedocs.io/) for practicing foundational data-processing patterns.

## What’s Included

| Script          | Description                                                              |
|-----------------|--------------------------------------------------------------------------|
| `wordcount.py`  | Basic word-frequency counter (strips punctuation and lowercases words)  |
| `song_count.py` | Counts how many times each song appears in a list of song plays         |
| `songplays.txt` | Sample input data for the song counting job                             |

## Tech Stack

- Python 3
- [mrjob](https://mrjob.readthedocs.io/) – MapReduce framework for Python

## Setup

```bash
pip install -r requirements.txt
Usage
Word count example:
Bashpython wordcount.py some_text_file.txt
Song play count example:
Bashpython song_count.py songplays.txt
