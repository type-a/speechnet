# SpeechNET

End-to-End Automatic Speech Recognition 

## Architecture 

This model is based on the state of the art end-to-end speech recognotion system by google reseach. But rather just havig a single network approach, it has multiple pipeline and an end search algorithm to choose the appropriate phenomes.

![model architecture](https://raw.github.com/golu-golu/speechnet/blob/master/images/architecture.png)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. This code is tested in Ubuntu 16.04 and Windows 10 with Python 3.6

```
git clone https://github.com/golu-golu/speechnet/
cd speechnet
python main.py
```

### Prerequisites

What things you need to install the software and how to install them

```
pip install -r requirements.txt
```

### Installing

A step by step series of examples that tell you have to get a development env running

To run with pretrained network

```
python main.py
```

To train locally and test

```
python train/train.py
python main.py
```

To test with single model file

```
python test_run.py -m  sound.mp3 
```
## Running the tests

To run automated test run with 
```
python main.py
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```


## Built With

* [Tensorflow](http://www.dropwizard.io/1.0.2/docs/) - Deep Leaning Framwork
* [Scipy](https://maven.apache.org/) - Math :)
* [Audio](https://rometools.github.io/rome/) - Audio Processing 


