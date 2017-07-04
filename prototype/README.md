# Event Detector Prototype
This prototype is the first approach for the `Event Detector` component. 
This component process video recordings with the exercise perfomance, generating an output file with the sequence of observable events detected.

## Setup

We'll use Python 2.7.

### RECOMMENDED

First of all, we recommend to install and use [Anaconda](https://www.continuum.io/downloads) python distribution.

Then, create a Python virtualenv so needed libraries don't affect system libraries:

Note that file system paths might differ in your computer.

```bash
conda create -n supervasion python=x.x anaconda
source activate supervasion
```

### Prototype dependencies

**Note:** Make sure that you have activated your `supervasion` virtualenv (`source activate supervasion`).

OpenCV 2.4.12
```bash
conda install -c jjhelmus opencv=2.4.12
```

For libraries dependency installation, you can execute the following command:
```bash
pip install -r requirements.txt
```

## Running the prototype

**Note:** Make sure that you have activated your `supervasion` virtualenv (`source activate supervasion`).

```bash
python main.py -n videos/exercise_1/video_example_cam_1.mp4 videos/exercise_1/video_example_cam_2.mp4
```

