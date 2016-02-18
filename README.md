# digoie-annotation

A python project to annotate person name or phone number based on open information extraction technology.

## Basic Features

- Fetch data by elastic search from DIG database, run it on ReVerb and get extractions.
- Extract features and build feature vectors to generate training and testing datasets for machine learning process.
- Automatically labeling based on given names.
- Integrate scikit-learn library ot train and test classifers, such as Decision Tree, random forest, ada boost, svm, and naive bayes.
- Test classifers on random datasets that contain phone numbers

## Usage

1. Download this repository

2. Install package
```
    sudo python setup.py install
```
3. Open terminal and use command to run this program
```
    Usage:
        digoie tcp <host> <port> [--timeout=<seconds>]
        digoie serial <port> [--baud=<n>] [--timeout=<seconds>]
        digoie (-i | --interactive)
        digoie (-h | --help | --version)
        digoie stream
        digoie dataset
        digoie classifier [--mla=<name>] [--min_df=<min_percent>] [--max_df=<max_percent>]
        digoie predict [--sentence=<string>]

    Options:
        -i, --interactive  Interactive Mode
        -h, --help  Show this screen and exit.
        --baud=<n>  Baudrate [default: 9600]
        --mla=<name>  machine learning algorithms
```
4. Have a look for the generated dataset and report at your home folder, named dig_openie








