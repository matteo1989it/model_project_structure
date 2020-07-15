# model_project_structure

<a href="https://martinfowler.com/articles/cd4ml/ml-pipeline-1.png">
ML pipeline by Martin Fawler
</a>
<a href="https://www.w3schools.com">
<img border="0" alt="W3Schools" src="https://martinfowler.com/articles/cd4ml/ml-pipeline-1.png" width="100" height="100">
</a> 

Example of basic ML pipeline structure, derived from [this](https://towardsdatascience.com/i-had-no-idea-how-to-build-a-machine-learning-pipeline-but-heres-what-i-figured-f3a7773513a) Medium article.

## Hierarchy

- **artifacts**
  - **train** : Logfiles, trained models
  - **test**  : Logfiles
- **datasets** : Data loading scripts
- **experiments** : Configuration files
- **models** : Scripts defining how the model looks like
- **optimizers** : Scripts defining the optimizeres
- **train** : Script to run the training
