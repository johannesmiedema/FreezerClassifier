![cmd](https://github.com/johannesmiedema/FreezerClassifier/actions/workflows/R-CMD-check.yaml/badge.svg)

# anxiotraitR
anxiotraitR is an R package which implements sex-specific machine learning models for classifying mice into sustained and phasic freezing reponders following aversive auditory conditioning (AAC) [1]. 

<img width="1070" alt="workflow" src="https://github.com/johannesmiedema/FreezerClassifier/assets/105965619/23cf17b1-947c-490f-8a56-8ee37016cca4">

## Installation
This package can be directly installed from github using devtools:
```
if(!require(devtools)){
    install.packages("devtools")
    library(devtools)
}
devtools::install_github("johannesmiedema/anxiotraitR")
```

## Usage 
A detailed explanation of how to use anxiotraitR is available in the package vignette: https://johannesmiedema.github.io/anxiotraitRDoc/ 

## Citation
Please remember to cite anxiotraitR if you use it in your analysis.

```
Miedema J, Lutz B, Gerber S, Kovlyagina I & Todorov H. Balancing ethics and statistics: Machine learning facilitates highly accurate classification of mice according to their trait anxiety with reduced samples sizes (2025).
```

## References 
[1] Kovlyagina I, Wierczeiko A, Todorov H, Jacobi E, Tevosian M, et al. (2024) Leveraging interindividual variability in threat conditioning of inbred mice to model trait anxiety. PLOS Biology 22(5): e3002642. https://doi.org/10.1371/journal.pbio.3002642
