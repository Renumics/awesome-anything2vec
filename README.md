# Awesome data2vec

Representation learning for industrialAI

## :factory: What is industrial AI ?
Data-driven methods that improve product development and manufacturing are often referred to as industrial AI. This umbrella unites many different applications such as quality control, condition monitoring, predictive maintenance, process optimization, robotics, generative design, or requirement analysis. Typical tasks within these applications are outlier/anomaly detection, event detection, performance forecasting or root cause analysis.

##  :compass: Why representation learning?
Representation learning allows to convert raw, unstructured data into expressive vectorial representations. That is why these techniques are also called x2vec, data2vec or anything2vec. The vector representations are directly useful in many tasks: Data exploration, anomaly detection or root cause analysis. Data efficient ML models can be built by using the vector representations as features for a classification or regression model. 

## :dart: Goal of this repository
This list aims to provide a hands-on overview over data2vec methods. Our goal is to provide a list of methods that are easy to use and work great in practice. While the methods are generally applicable, we focus on data types and scenarios that are typical in industrial AI.

We include both links to pre-trained foundational models as well as to models that are trained on a specific dataset using self-supervision. For each model, we provide the following additional info:

- How much expert knowledge is required to use and parameterize the model: We distinguish between three difficulty levels: Citizen data scientist :woman_student:, ML engineer  	:woman_mechanic:, ML researcher :woman_scientist:
- How coding effort is required to use the model (in T-shirt sizes): S: < 5 lines, M< 20 lines, L< 100 lines, XL > 100 lines 
- An example for the model 


## :open_hands: Contributing
Do you think something is missing? Please help contribute to this list by contacting us or by adding a pull request.


# Images

| Name | Description | Difficulty | Effort | Examples |
| ---- | ----------- | ----- | ---- | ------- |
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


