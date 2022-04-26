# Introduction to Azure Machine Learning Pipelines

The following notebooks provide an introduction to a concept in Azure Machine Learning Pipelines. They will introduce you to core Azure Machine Learning Pipelines features. 
These notebooks below are designed to go in sequence.

## Examples available

Test Status is for branch - **_sdk-preview_**
|Area|Sub-Area|Notebook|Description|Status|
|--|--|--|--|--|
|jobs|pipelines|[pipeline_with_components_from_yaml](1a_pipeline_with_components_from_yaml/pipeline_with_components_from_yaml.ipynb)|Create pipeline with CommandComponents from local YAML file|[![pipeline_with_components_from_yaml](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1a_pipeline_with_components_from_yaml-pipeline_with_components_from_yaml.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1a_pipeline_with_components_from_yaml-pipeline_with_components_from_yaml.yml)|
|jobs|pipelines|[pipeline_with_python_function_components](1b_pipeline_with_python_function_components/pipeline_with_python_function_components.ipynb)|Create pipeline with dsl.command_component|[![pipeline_with_python_function_components](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1b_pipeline_with_python_function_components-pipeline_with_python_function_components.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1b_pipeline_with_python_function_components-pipeline_with_python_function_components.yml)|
|jobs|pipelines|[pipeline_with_hyperparameter_sweep](1c_pipeline_with_hyperparameter_sweep/pipeline_with_hyperparameter_sweep.ipynb)|Use sweep (hyperdrive) in pipeline to train mnist model using tensorflow|[![pipeline_with_hyperparameter_sweep](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1c_pipeline_with_hyperparameter_sweep-pipeline_with_hyperparameter_sweep.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1c_pipeline_with_hyperparameter_sweep-pipeline_with_hyperparameter_sweep.yml)|
|jobs|pipelines|[pipeline_with_non_python_components](1d_pipeline_with_non_python_components/pipeline_with_non_python_components.ipynb)|Create a pipeline with command function|[![pipeline_with_non_python_components](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1d_pipeline_with_non_python_components-pipeline_with_non_python_components.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1d_pipeline_with_non_python_components-pipeline_with_non_python_components.yml)|
|jobs|pipelines|[pipeline_with_registered_components](1e_pipeline_with_registered_components/pipeline_with_registered_components.ipynb)|Register component and then use these components to build pipeline|[![pipeline_with_registered_components](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1e_pipeline_with_registered_components-pipeline_with_registered_components.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-1e_pipeline_with_registered_components-pipeline_with_registered_components.yml)|
|jobs|pipelines|[train_mnist_with_tensorflow](2a_train_mnist_with_tensorflow/train_mnist_with_tensorflow.ipynb)|Create pipeline using components to run a distributed job with tensorflow|[![train_mnist_with_tensorflow](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2a_train_mnist_with_tensorflow-train_mnist_with_tensorflow.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2a_train_mnist_with_tensorflow-train_mnist_with_tensorflow.yml)|
|jobs|pipelines|[train_cifar_10_with_pytorch](2b_train_cifar_10_with_pytorch/train_cifar_10_with_pytorch.ipynb)|Get data, train and evaluate a model in pipeline with Components|[![train_cifar_10_with_pytorch](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2b_train_cifar_10_with_pytorch-train_cifar_10_with_pytorch.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2b_train_cifar_10_with_pytorch-train_cifar_10_with_pytorch.yml)|
|jobs|pipelines|[nyc_taxi_data_regression](2c_nyc_taxi_data_regression/nyc_taxi_data_regression.ipynb)|Build pipeline with components for 5 jobs - prep data, transform data, train model, predict results and evaluate model performance|[![nyc_taxi_data_regression](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2c_nyc_taxi_data_regression-nyc_taxi_data_regression.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2c_nyc_taxi_data_regression-nyc_taxi_data_regression.yml)|
|jobs|pipelines|[image_classification_with_densenet](2d_image_classification_with_densenet/image_classification_with_densenet.ipynb)|Create pipeline to train cnn image classification model|[![image_classification_with_densenet](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2d_image_classification_with_densenet-image_classification_with_densenet.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2d_image_classification_with_densenet-image_classification_with_densenet.yml)|
|jobs|pipelines|[image_classification_keras_minist_convnet](2e_image_classification_keras_minist_convnet/image_classification_keras_minist_convnet.ipynb)|Create pipeline to train cnn image classification model with keras|[![image_classification_keras_minist_convnet](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2e_image_classification_keras_minist_convnet-image_classification_keras_minist_convnet.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2e_image_classification_keras_minist_convnet-image_classification_keras_minist_convnet.yml)|
|jobs|pipelines|[rai_pipeline_sample](2f_rai_pipeline_sample/rai_pipeline_sample.ipynb)|Create sample RAI pipeline|[![rai_pipeline_sample](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2f_rai_pipeline_sample-rai_pipeline_sample.yml/badge.svg?branch=sdk-preview)](https://github.com/Azure/azureml-examples/actions/workflows/sdk-jobs-pipelines-2f_rai_pipeline_sample-rai_pipeline_sample.yml)|