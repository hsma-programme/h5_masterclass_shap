# **Welcome to the HSMA Masterclass on SHAP - eXplainable AI (XAI)**.

## Module structure

> The masterclass lecture slides are available in this repo, and the lecture is scheduled to take place on Tuesday 23 May, 0930 - 1230.

## Learning outcomes

**By the end of the class you will have...**

* An understanding how XAI works with LIME and SHAP
* Hands on experience interpreting ML models using the SHAP library; and
* Be able to interpret the outputs of SHAP.

## Description of materials.

Following a short introductory presentation (`Masterclass Explainable AI Student Slides`.pdf) we'll get straight into a guided code along before you'll work within your PSGs to complete an exercise.

You can either attempt these exercises via an online environment called [BinderHub](https://mybinder.org/v2/gh/hsma5/masterclass_shap/HEAD) (no local installs required). Otherwise, to get the correct libraries and versions locally it is recommended that you use the provided conda `environment.yml` file. To create and activate the `shap_xai` environment follow the instructions below.

To create environment. Navigate to the `binder` folder.

`conda env create -f environment.yml`

To activate environment:

`conda activate shap_xai`

To deactivate:

`conda deactivate`

To remove the environment (if desired):

`conda env remove -n shap_xai`

### Code along notebooks

During the live session, we'll be working our way through a code along notebook; this can be found in the `code_along\` directory.

### Practical exercises notebook

The exercise notebook can be found in `exercise\` directory. In the exercise notebook you will work to solve a scenario focusing on the Iris data set multi classification problem. This will follow a similar structure to the code along exercise. This exercise will be completed within your Peer Support Groups.

### Solutions to exercise

> Solutions to the practical exercise will be released following the live lecture.
