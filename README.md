# Puzzle Piece Segmentation

This repo contains implementations for a GMM and U-Net image segmentation models. 


# How to run

Please create a virtual environment and install the dependencies by running 
```bash
pip install -r requirements.txt
```

Launch Jupyter and open either `GMM.ipynb` or `UNET.ipynb`. Running all cells in order will load the data, run hyperparameter optimization, train the best model and evaluate the model.


# Running saved U-Net Models

If you would like to run the models used to obtain the results achieved in the report, please download the models contained at https://drive.google.com/drive/folders/1r27ycWhwER2yGBruUJhT3GszLudgcKWl?usp=sharing. The notebook will load the model and run the evaluation. 
