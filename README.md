# Project-Template for IWS 276 Labor

Short introduction to project assigment.

<p align="center">
  Screenshot / GIF <br />
  Link to Demo Video
</p>

> This work was done by Autor 1, Autor2, Autor 3 during the IWI276 Autonome Systeme Labor at the Karlsruhe University of Applied Sciences (Hochschule Karlruhe - Technik und Wirtschaft) in SS 2020. 

## Table of Contents

* [Requirements](#requirements)
* [Prerequisites](#prerequisites)
* [Pre-trained model](#pre-trained-model)
* [Running](#running)
* [Acknowledgments](#acknowledgments)

## Requirements
* Python 3.7 (or above)
* OpenCV 4.0 (or above)
* Jetson Nano | Jetson TX2
* Jetpack 4.2
> [Optional] ...

## Prerequisites
1. Install requirements:
```
pip install -r requirements.txt
```

## Pre-trained models <a name="pre-trained-models"/>

Pre-trained model is available at pretrained-models/

## Running

To run the demo, pass path to the pre-trained checkpoint and camera id (or path to video file):
```
python src/demo.py --model model/student-jetson-model.pth --video 0
```
> Additional comment about the demo.

## Acknowledgments

This repo is based on
  - [Source 1](https://github.com/)
  - [Source 2](https://github.com/)

Thanks to the original authors for their work!

## Contact
Please email `mickael.cormier AT iosb.fraunhofer.de` for further questions.
