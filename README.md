# Topological SHAP Project

Previous work has used deep learning models to predict persistent homology–based representations of data. However, we still are not sure whether these models actually learn topological structure or are just overfit to the output vectorization. We evaluate this by analyzing which input regions most influence the predicted persistence landscape using SHAP.

We train a DenseNet-121 model to predict 300-dimensional persistence landscape vectors derived from cubical filtrations on grayscale versions of scene images. We then compare the SHAP attribution maps to the hole locations extracted from persistent homology alone.

## Contents

- `Fanning_Topological_SHAP.ipynb`  
  - Main end-to-end pipeline notebook. Includes data loading, preprocessing, modeling, and SHAP-based explainability.
- `Fanning_Statistics_Poster_4.pptx`  
  - Final version of the conference poster presented at C Day and Analytics Day.
- `Fanning_Dataset_Explanation.docx`  
  - Supplementary document outlining dataset details and exploratory analysis.
- `logs/`  
  - Contains source references and GPT interaction logs.
- `old/`  
  - Archived materials from earlier commits. Not used in current version.
- `cday/`
  - Contains all of the supplementary materials from the C-Day submission.