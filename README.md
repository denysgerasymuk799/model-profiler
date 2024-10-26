# Model Profiler


## 📜 Description

**Model Profiler** is a Python library for in-depth profiling of model performance across overall and disparity dimensions. 
In addition to its metric computation capabilities, the library provides an interactive tool 
to streamline responsible model selection and generate nutritional labels for ML models.

The library was developed based on three fundamental principles: 

1) easy extensibility of model analysis capabilities;

2) compatibility to user-defined/custom datasets and model types;

3) simple composition of disparity metrics based on the context of use.

The framework decouples model auditing into several stages, including: **subgroup metric computation**, **disparity metric composition**,
and **metric visualization**. This gives data scientists more control and flexibility to use the library
for model development and monitoring post-deployment.


## 💡 List of Features

* Profiling of all normatively important performance dimensions: accuracy, stability, uncertainty, and fairness
* Ability to analyze non-binary sensitive attributes and their intersections
* Convenient metric computation interfaces: an interface for multiple models, an interface for multiple test sets, and an interface for saving results into a user-defined database
* Interactive visualizer that profiles dataset properties related to protected groups, computes comprehensive [nutritional labels](http://sites.computer.org/debull/A19sept/p13.pdf) for individual models, compares multiple models according to multiple metrics, and guides users through model selection
* Compatibility with [pre-, in-, and post-processors](https://aif360.readthedocs.io/en/latest/modules/algorithms.html#) for fairness enhancement from AIF360
* An `error_analysis` computation mode to analyze model stability and confidence for correct and incorrect prodictions broken down by groups
* Metric static and interactive visualizations
* Data loaders with subsampling for popular fair-ML benchmark datasets
* User-friendly parameters input via config yaml files 
* Integration with PyTorch Tabular


## 📝 License

**Model Profiler** is free and open-source software licensed under the [MIT License](https://github.com/denysgerasymuk799/model-profiler?tab=MIT-1-ov-file).
