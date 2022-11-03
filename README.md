# CSV to JSON

## Usage

```sh

./convert filename.csv

```

Where `filename` is the full path to your csv file  
Output csv file with new column will have the name `filename.output.csv`  
Json file output also follows the same naming convention.  

> Dev environment - Ubuntu 22.04

## Synopsis

The program takes a csv filename as user input and converts the csv file rows into json objects.  
It then calculates a SHA256 hash of the json objects and appends a new column `Hash` to a copy of the supplied csv file.  

## Getting started

### Prerequisites

Python - `3.x`
pip - `22.x`

* Clone this repo locally

```sh

git clone https://github.com/beingnile/chip-json

```

* Navigate to the directory

```sh

cd chip-json

```

* Install required packages

```sh

pip install -r Requirements.txt

```

* To run the script

```sh

./convert filename.csv

```

## AUTHORS

Nile Okomo
