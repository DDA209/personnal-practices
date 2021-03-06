# Developpement personnal practices

## Summary

  ### 1. [Naming](#naming):
  1. [Folders naming](#folders-naming)
  1. [Files naming](#files-naming)
  1. [Git branch naming](#git-branch-naming)
  ### [Glossary](#glossary-1)

## Naming
All naming practices in my new projects

  ### Folders naming
  [Folders](#folder) names are written according to the following guidelines:
  - Only with alphabetical and non accentuated letter
  - Never start with a number, number can start from the second letter
  - Start with a lowercase letter
  - Use snake case 🐍 if named with many words
  - Special characters are replaced with *dash* **-**
  - Initials and acronyms should be written in lowercase
  - Naming should be descriptive and consistent in the context of the use of the folder
  - Extensions are strongly discouraged and should be used for specific used and documented purposes
  - use plural if folder contain many elements described by it's name

        folders tree example:
        ./omq
        ./omq/components
        ./omq/components/core
        ./omq/components/core/buttons
        ./omq/components/core/buttons/small-button
        ./omq/components/core/buttons/big-button

  ### Files naming
  Files names are written according to the following guidelines:
  - Only with alphabetical and non accentuated letter
  - Never start with a number, number can start from the second letter
  - Start with a lowercase letter, except:
    - components, 
    - models and
    - other files for specific and documented purposes
  who start with an uppercase 
  - Use snake case 🐍 if named with many words
  - Special characters are replaced with *dash* **-**
  - Initials and acronyms should be written in lowercase
  - Naming should be descriptive and consistent in the context of the use of the file
  - Naming must contain only one dot, it preced the file extension
  - Usage of multiple dots is strongly discouraged and must be used for specific and documented purposes
  - Plural usage must be defined

        files example:
        common-fields.js
      
## Glossary
#### Folder
logical file container (not egal to directory) *e.g ./that-s-a-folder/* or *D:\datas\an-amzing-project\that-s-a-folder\*
