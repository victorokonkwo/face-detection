# Face detection task

## Usage

Download source and data from [download page](https://github.com/vslutov/face-detection/releases),
open [./Face_Detection.ipynb](Face_Detection.ipynb) and do task. It's easy.



## Files

This repository consist of multiple files:

- `Face_Detection.ipynb` -- main task, read and do.
- `get_data.py` -- script to download data for task, run automatically from main task.
  You don't need download data manually.
- `scores.py` -- scores, which are using in main task.
- `graph.py` -- graph plotting and image showing functions.
- `prepare_data.ipynb` -- prepare data to train and test, you may run this script and repeat
  learning-test procedure to make sure that model haven't over-fitting.

## Dataset

Dataset, used in this task is processed [FDDB dataset](http://vis-www.cs.umass.edu/fddb/).
Processing explained in [./Face_Detection.ipynb](Face_Detection.ipynb) and defined in [./prepare_data.ipynb](prepare_data.ipynb)

## Authors
- Prepared by Vladimir Lutov: [github.com/vslutov](https://github.com/vslutov), [vladimir.lutov@graphics.cs.msu.ru](mailto:vladimir.lutov@graphics.cs.msu.ru)
