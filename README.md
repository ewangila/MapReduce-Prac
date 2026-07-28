# MapReduce on Romeo and Juliet

A collection of Python MapReduce jobs built with mrjob that demonstrate foundational and intermediate data-processing patterns on the text of Romeo and Juliet.

## What’s Included

| Script            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| wordcount.py    | Basic word-frequency counter (strips punctuation, lowercases)               |
| wordcountmax.py | Multi-step job that finds the single most frequent word                     |
| top5.py         | Multi-step job that returns the top 5 most frequent words (stop words filtered) |
| top10.py        | Same as above but returns the top 10                                        |
| countrj.py      | Counts occurrences of the names “Romeo” and “Juliet”                        |
| song_count.py   | Simple line-count aggregator (leftover practice script)                     |

## Tech Stack

- Python 3
- [mrjob](https://mrjob.readthedocs.io/) – MapReduce framework for Python

## Setup

```bash
pip install -r requirements.txt
