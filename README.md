# MapReduce Data Analysis

This project demonstrates the use of the **MapReduce** programming model in Python to efficiently process and analyze large datasets. The scripts use the `mrjob` library to perform distributed data processing tasks.

## Project Structure

```
├── wordcount.py      # Counts the frequency of words in a dataset
├── song_count.py     # Calculates the total number of times each song was played
├── songplays.txt     # Sample dataset used for song play analysis
└── README.md
```

## Features

- Count word frequencies from text files.
- Analyze song play data using MapReduce.
- Demonstrates the Mapper and Reducer workflow with Python.
- Built using the `mrjob` framework.

## Requirements

- Python 
- mrjob

Install the required dependency:

```bash
pip install mrjob
```

## Usage

### Word Count

```bash
python wordcount.py <input_file>
```

Example:

```bash
python wordcount.py text.txt
```

### Song Play Count

```bash
python song_count.py songplays.txt
```

## Example Output

**Word Count**

```
hello    15
world    8
python   5
```

**Song Play Count**

```
Song A    120
Song B     95
Song C     74
```

## Skills Demonstrated

- Python
- MapReduce
- Data Processing
- Big Data Concepts
- `mrjob`

## License

This project is open source and available under the MIT License.
