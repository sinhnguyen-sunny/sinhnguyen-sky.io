---
layout: post
title: "🚀📱v1 ML Ecosystem - TensorFlow vs PyTorch: A Quick Revision🚀📱"
cover-img: /assets/img/v1_ml_ecosys_wallpaper.jpeg
thumbnail-img: /assets/img/v1_ml_ecosys.jpeg
share-img: /assets/img/v1_ml_ecosys_wallpaper.jpeg
tags: [ml_ecosys]
comments: true
---

When it comes to deep learning frameworks, TensorFlow and PyTorch are two of the most popular choices. 

## Overview of TensorFlow vs PyTorch

PyTorch is the preferred choice of the majority of researchers, as evident from the availability of models written in PyTorch compared to TensorFlow on platforms like Hugging Face and Papers with Code [source](https://www.assemblyai.com/blog/pytorch-vs-tensorflow-in-2023/). Researchers appreciate PyTorch for its user-friendly interface, dynamic computational graph, and extensive community support.

On the other hand, TensorFlow excels in deploying trained models to production [source](https://www.simplilearn.com/keras-vs-tensorflow-vs-pytorch-article#:~:text=TensorFlow%20offers%20better%20visualization%2C%20which,to%20the%20TensorFlow%20Serving%20framework). It provides advanced visualization tools and frameworks like TensorFlow Serving for model deployment in inference scenarios. TensorFlow also offers TensorFlow Lite for running models on edge devices and TensorFlow.js for executing models directly in JavaScript on a browser.

For AI engineers, the choice between PyTorch and TensorFlow depends on specific requirements. If access to state-of-the-art (SOTA) models available only in PyTorch is crucial, the recent release of TorchServe makes PyTorch a suitable option. However, to deploy a converted PyTorch model within TensorFlow's deployment workflows, the ONNX conversion can be employed. Another option for deploying/serving PyTorch models in production is using NVIDIA TensorRT.

To explore more details and comparisons between TensorFlow and PyTorch, you can refer to the following link: [PyTorch vs TensorFlow by KnowledgeHut](https://www.knowledgehut.com/blog/data-science/pytorch-vs-tensorflow)

## Deployment Capabilities

### TensorFlow:

- [**TensorFlow Serving**](https://www.tensorflow.org/tfx/serving/serving_basic): Consumes TensorFlow SavedModels and accepts inference requests over REST or gRPC interfaces. It can serve multiple models or versions simultaneously.
- [**TensorFlow Lite**](https://www.tensorflow.org/lite): Enables the use of models on edge devices such as microcomputers, microcontrollers, or cell phones.
- [**TensorFlow.js**](https://www.tensorflow.org/js): Allows training and running inference with deep learning models directly in JavaScript, making it possible to execute models directly on a browser.

### PyTorch:

- [**TorchServe**](https://pytorch.org/serve/): A highly scalable serving framework that can handle the deployment of multiple models simultaneously.
- [**PyTorch Mobile**](https://pytorch.org/mobile/home/): The PyTorch equivalent of TensorFlow Lite, enabling the deployment of PyTorch models on resource-constrained devices.

## Ecosystem and Domain Libraries

TensorFlow offers a comprehensive ecosystem with various domain-specific libraries and frameworks, including:

- [**Keras**](https://keras.io/): A high-level API for TensorFlow, providing an easy-to-use interface for building and training models.
- [**TF Extended (TFX)**](https://www.tensorflow.org/tfx): Designed for building MLOps pipelines, facilitating end-to-end machine learning workflows.
- [**TensorFlow Hub**](https://www.tensorflow.org/hub): A repository of trained machine learning models ready for fine-tuning and deployment.
- [**TensorFlow Recommenders**](https://www.tensorflow.org/recommender): A library specifically for building recommender systems with TensorFlow.
- [**GNN (Graph Neural Networks)**](https://github.com/tensorflow/gnn): Tools for working with graph-based data and applying graph neural networks.
- [**TF Agents**](https://github.com/tensorflow/agents): A library for reinforcement learning applications.
- [**TF Datasets (TFDS)**](https://www.tensorflow.org/datasets): A collection of ready-to-use datasets.
- [**TF Playground**]([https://playground.tensorflow.org/?_gl=1*aygalk*_ga*MTg0NzQ3NjMxNi4xNjc0NzUxNDcx*_ga_W0YLR4190T*MTY3NjEyNDQwNC4xOC4xLjE2NzYxMjcxNTAuMC4wLjA.#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=NaN&regularizationRate=0&noise=0&networkShape=4,2&seed=0.04620&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false): An interactive platform for tinkering with and visualizing neural network training.

PyTorch also has its own set of domain libraries, including:

- [**TorchVision**](https://pytorch.org/vision/stable/index.html): PyTorch's computer vision library.
- [**TorchText**](https://pytorch.org/text/stable/index.html): An in-built domain library for text-related tasks.
- [**TorchAudio**](https://pytorch.org/audio/stable/index.html]): PyTorch's library for audio-related tasks.
- [**TorchRec**](https://pytorch.org/torchrec/): PyTorch's newest domain library for recommendation engines powered by deep learning.
- [**PyTorch Lightning**](https://www.pytorchlightning.ai/): An API for PyTorch that allows faster experimentation (sometimes called the Keras of PyTorch).
- [**PyTorch XLA**](https://pytorch.org/xla/release/1.6/index.html): For running models on accelerator devices like TPUs.
- [**Detectron2**](https://github.com/facebookresearch/detectron2): A PyTorch library for object detection and segmentation tasks.
- [**Albumentations**](https://github.com/albumentations-team/albumentations): A popular framework for computer vision data augmentation methods.
- [**FLAIR**](https://github.com/flairNLP/flair): A simple framework for natural language processing with PyTorch.
- [**AllenNLP**](https://allenai.org/allennlp/team): Another popular library for NLP.
- [**PyTorch Hub**](https://pytorch.org/docs/stable/hub.html?ref=assemblyai.com): A research-oriented platform for sharing repositories with pre-trained models.

## Cheat sheets:

- PyTorch Cheat Sheets: [Link 1](https://pytorch.org/tutorials/beginner/ptcheat.html), [Link 2](https://www.simonwenkel.com/publications/cheatsheets/pdf/cheatsheet_pytorch.pdf)
- TensorFlow Cheat Sheets: [Link 1](https://www.altoros.com/visuals/tensorflow-cheat-sheet/), [Link 2](https://github.com/louishenrifranc/Tensorflow-Cheatsheet)

Additional discussions and resources can be found on platforms like Kaggle: [Kaggle Discussion](https://www.kaggle.com/discussions/general/298280)
