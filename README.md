# Scalable Recommendation System with AWS SageMaker

A scalable recommendation system built with **MXNet**, **Gluon**, and **AWS SageMaker**. The notebook covers data preparation, model training, deployment on SageMaker, and evaluation of recommendation quality.

## Tech Used

- Python
- Apache MXNet / Gluon
- AWS SageMaker
- NumPy, Pandas

## Project Structure

```
Project.ipynb   # Main notebook — data prep, training, deployment, and evaluation
```

## How to Run

1. **Local exploration:** Install dependencies and open the notebook:
   ```bash
   pip install mxnet numpy pandas
   jupyter notebook Project.ipynb
   ```
2. **Full pipeline on AWS:** Run the notebook inside an AWS SageMaker notebook instance to take advantage of managed training and deployment. You will need an AWS account with SageMaker permissions.
