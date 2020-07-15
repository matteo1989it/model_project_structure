# model_project_structure

<a href="foo">
*bar*
</a>


Example of basic ML pipeline structure, derived from [this](https://towardsdatascience.com/i-had-no-idea-how-to-build-a-machine-learning-pipeline-but-heres-what-i-figured-f3a7773513a) Medium article.

## Hierarchy

**├── artifacts**

**│   ├── train** : Logfiles, trained models

**│   └── test**  : Logfiles

**├── datasets** : Data loading scripts
**├── experiments** : Configuration files
**├── models** : Scripts defining how the model looks like
**├── optimizers** : Scripts defining the optimizeres
**└── train** : Script to run the training
