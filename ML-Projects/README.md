# ML-Projects

A collection of machine learning and deep learning notebooks demonstrating experiments, tutorials, and small projects. This folder contains exploratory data analysis (EDA) examples, model-building pipelines, PyTorch walkthroughs, transfer learning experiments, and an introductory reinforcement learning notebook.


## Notebooks 

- [BuffaloInventory.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/BuffaloInventory.ipynb)  
  Inventory / demand analysis case study — data cleaning, exploratory analysis, feature engineering and baseline forecasting/classification experiments 

- [EDA.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/EDA.ipynb)  
  General exploratory data analysis examples and visualizations demonstrating common EDA techniques and best practices.

- [Python-Revision.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/Python-Revision.ipynb)  
  Python fundamentals and quick revision focused on concepts useful for ML practitioners (data structures, comprehensions, functions, basic libraries).

- [Reinforcement-Learning.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/Reinforcement-Learning.ipynb)  
  Introductory reinforcement learning examples — implementing basic agents (e.g., Q-learning / policy gradient) and experiments using OpenAI Gym-like environments.

- [data-analysis.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/data-analysis.ipynb)  
  End-to-end data analysis pipeline: loading data, preprocessing, visualization, feature engineering and summary of findings.

- [data_analysis_logistic_regression.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/data_analysis_logistic_regression.ipynb)  
  Classification example using logistic regression — data preparation, model training, evaluation (confusion matrix, ROC), and interpretation.

- [pytorch-revision.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/pytorch-revision.ipynb)  
  PyTorch fundamentals and short tutorial: tensors, autograd, building simple neural networks and training loops.

- [resnet34_oxford_flowers.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/resnet34_oxford_flowers.ipynb)  
  Transfer learning using ResNet-34 on the Oxford Flowers dataset — dataset preparation, fine-tuning, augmentation and evaluation.

- [simple_nn_pipeline.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/simple_nn_pipeline.ipynb)  
  Simple neural network pipeline example: data loader, model definition, training, validation and model saving/loading.

- [vgg_classification.ipynb](https://github.com/pradeep-ramola/AI-ML/blob/e50ec7429a6f51faf1d4d056e1ef3af99a41db18/ML-Projects/vgg_classification.ipynb)  
  VGG-based image classification experiments and fine-tuning workflow for computer vision tasks.

## Usage

To view and run these notebooks locally:

1. Clone the repository (if you haven't already):
   ```bash
   git clone https://github.com/pradeep-ramola/AI-ML.git
   cd AI-ML/ML-Projects
   ```

2. Create a Python virtual environment and activate it:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .venv\Scripts\activate      # Windows (Powershell)
   ```

3. Install dependencies (recommended to use a requirements file — see Requirements below). Example:
   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a requirements.txt, install the common packages manually (see Requirements).

4. Start Jupyter (Lab or Notebook) and open the desired notebook:
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

5. Run cells top-to-bottom. For heavy training notebooks (ResNet/VGG), consider using a GPU runtime or Google Colab.

Quick tips:
- Use smaller subsets of data or fewer epochs when experimenting locally to save time.
- For image experiments, make sure required datasets are downloaded or adjust paths accordingly.
- Consider running the deep learning notebooks on Colab (free GPU) if no local GPU is available.

## Requirements

Recommended Python version: 3.8 or newer.

Minimum recommended packages (example; some notebooks may need extra packages listed below):

```
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
jupyterlab
notebook
tqdm
pillow
```

If you plan to run the PyTorch / CV / RL notebooks:

```
torch      # install the appropriate build for your CUDA / CPU
torchvision
gym        # for reinforcement learning examples (optional)
tensorboard (optional)
```



