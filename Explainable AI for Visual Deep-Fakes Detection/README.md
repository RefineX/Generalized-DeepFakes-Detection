# Chapter 7: Explainable AI For Visual Deep-Fakes Detection

## 7.4 Dataset and Training
Notebook used: [training.ipynb](training.ipynb)
In this notebook, we trained the XceptionNet on the DFD dataset with a cropping scale of 2x where the face occupies not more than 60\% of the entire image for the purposes of exploring model interpretability.
## 7.6 Intermediate Activations
Notebook used: [Intermediate_Activations.ipynb](Intermediate_Activations.ipynb)
In this notebook, we visualized the intermediate activations for different layers of the trained model for an input image. We can observe various forms of edges present throughout the human face like the forehead, eyes, mouth, and jawline captured by the filters of the model.
## 7.7 Local Interpretable Model-Agnostic Explanations (LIME)
Notebook used: [LIME.ipynb](LIME.ipynb)
In this notebook, we present intepretable visualizations of our input image superimposed on the prediction based attention slice of our model using LIME.
## 7.8 Layer-wise Relevance Propagation (LRP)
Notebook used: [LRP.ipynb](LRP.ipynb)
In this notebook, we produce a heatmap in the input space indicating the relevance of each pixel contributing to the final classification outcome using LRP.
