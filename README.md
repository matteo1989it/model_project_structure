# model_project_structure
Example of basic ML pipeline structure, derived from [this](https://towardsdatascience.com/i-had-no-idea-how-to-build-a-machine-learning-pipeline-but-heres-what-i-figured-f3a7773513a) Medium article.


</a>
<a href="https://martinfowler.com/articles/cd4ml.html">
<img border="0" alt="ML pipeline by Martin Fawler" src="https://martinfowler.com/articles/cd4ml/ml-pipeline-1.png">
</a> 



## Hierarchy

- **artifacts**
  - **train** : Logfiles, trained models
  - **test**  : Logfiles
- **datasets** : Data loading scripts
- **experiments** : Configuration files
- **models** : Scripts defining how the model looks like
- **optimizers** : Scripts defining the optimizeres
- **train** : Script to run the training
