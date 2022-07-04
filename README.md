# Awesome data2vec

Representation learning for Industrial AI

## :factory: What is Industrial AI?
Data-driven methods that improve product development and manufacturing are often referred to as Industrial AI. This umbrella unites many applications such as quality control, condition monitoring, predictive maintenance, process optimization, robotics, generative design, and requirement analysis. Typical tasks within these applications are outlier/anomaly detection, event detection, performance forecasting, or root cause analysis.

##  :compass: Why representation learning?
Representation learning allows to convert raw, unstructured data into expressive vectorial representations. These techniques are also called x2vec, data2vec, or anything2vec. They can be helpful for tasks such as data exploration, anomaly detection, or root cause analysis. Additionally, they enable the construction of data-efficient models using vector representations as a feature. 

## :dart: Goal of this repository
This list aims to provide a hands-on overview of data2vec methods. Our focus here is to provide a list of techniques that are easy to use and work great in practice. Additionally, they all apply to Industrial AI data and use cases.

We include links to pre-trained foundation models and models you can train on your own datasets using self-supervision.

For each model, we provide the following additional information:

- How popular the model or library is
- How coding effort is required to use the model (in T-shirt sizes): S: < 5 lines, M< 20 lines, L< 100 lines, XL > 100 lines 
- Resources such as hands-on examples, the corresponding paper, or a compact explanation of the method


## :open_hands: Contributing
Do you think something is missing? Please help contribute to this list by contacting us or adding a pull request.


# Images

| Name | Description | Popularity | Effort | Resources |
| ---- | ----------- | ---------- | ------ | --------- |
| [ResNet50](https://huggingface.co/microsoft/resnet-50) | Foundational ResNet model pre-trained on ImageNet-1k at resolution 224x224.  | :woman_student: | M| [MVTec Example] |
| [ViT(Vision Transformer)](https://huggingface.co/docs/transformers/model_doc/vit) | Self-supervised Vision Transformer was pre-trained using a resolution of 224x224  | :woman_scientist: | L | [MVTec Example] |

## Foundational models:
-	Resnet: CD | S | Example
-	ViT(Vision Transformer) ML | L | Example
## Self-supervised models
-	Simclr: ME | M | Example
-	BYOL: ME | M | Example


### Video 

### Audio (high-frequency time series)
#### Foundational models:
-	VGGIsh: CD | S | Example
#### Self-supervised models:
### Geometry
#### Foundational models:

#### Self-supervised models:

### Time series (medium frequency)
#### Foundational models:
#### Self-supervised models:
-	Signal to vec

### Time series (low frequency)
#### Foundational models:

#### Self-supervised models:


### Multimodal
#### Foundational models:

#### Self-supervised models:


