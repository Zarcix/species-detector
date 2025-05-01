# Species Detector

This repository is for a CNN that trains on a dataset that has images of different microorganisms.

## Training Phases

This project went through three phases:

1. Hyper Parameter Tuning
    - This step was done on a smaller [dataset](https://1drv.ms/u/s!AtgMuyZI0PWbggs_jMwKZeGxkuip?e=qyOR3r).
    - `modelTrainWeights.py` is the python file for this step
2. Full dataset training using hyper parameters
    - This step was done on the [full dataset]().
    - `modelTrainFull.py` is the python file for this step
3. Testing and verification using an augmented dataset
    - An augmented dataset was generated for this step.
    - To generate your own dataset, use `generateDataset.py`.
    - `modelEvaluate.py` was used for testing

## Model Selection

The best training model (model against original dataset) was [Fold 1](./Models/model_fold1.keras)

The best testing model (model against augmented dataset) was [Fold 9](./Models/model_fold9.keras)

## Results

![Results](./Results/The PC breakers ECPE 193A.svg)
<img src="./Results/The PC breakers ECPE 193A.svg">
