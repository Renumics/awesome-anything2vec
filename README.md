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

- How popular the model or library is.
- How coding effort is required to use the model (in T-shirt sizes): S: < 5 lines, M< 20 lines, L< 100 lines, XL > 100 lines.
- Wether the application of the model requires additional training on your own data.
- Resources such as hands-on examples, the corresponding paper, or a compact explanation of the method.


## :open_hands: Contributing
Do you think something is missing? Please help contribute to this list by contacting us or adding a pull request.


# Images

| Name | Description | Popularity | Effort | Training required | Resources |
| ---- | ----------- | ---------- | ------ | ----------------- | --------- |
| [OpenL3](https://github.com/marl/openl3) | OpenL3 is an open-source Python library for computing deep audio and image embeddings. | [![PyPI download month](https://img.shields.io/pypi/dm/openl3.svg)](https://pypi.python.org/pypi/openl3/) [![GitHub stars](https://img.shields.io/github/stars/marl/openl3.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/marl/openl3/stargazers/) | S | no | [[Github]](https://github.com/marl/openl3) [[Docs]](https://openl3.readthedocs.io/en/latest/?badge=latest) [[Example]](https://openl3.readthedocs.io/en/latest/tutorial.html#extracting-image-embeddings) |
 [towhee](https://docs.towhee.io/User%20Guides/Built-in%20Pipelines/image-embedding/) | Towhee is a framework that provides ETL for unstructured data using SoTA machine learning models. | [![PyPI download month](https://img.shields.io/pypi/dm/towhee.svg)](https://pypi.python.org/pypi/towhee/) [![GitHub stars](https://img.shields.io/github/stars/towhee-io/towhee.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/towhee-io/towhee/stargazers/) | S | no | [[Github]](https://github.com/towhee-io/towhee) [[Docs]](https://docs.towhee.io/) [[Snippet]](https://hub.towhee.io/towhee/image-embedding-resnet50) [[Example]](https://github.com/towhee-io/examples/tree/main/image/reverse_image_search) |
| [ResNet50](https://huggingface.co/microsoft/resnet-50) | Foundational ResNet model pre-trained on ImageNet-1k at resolution 224x224.  | :woman_student: | M| can | [MVTec Example] |
| [ViT(Vision Transformer)](https://huggingface.co/docs/transformers/model_doc/vit) | Self-supervised Vision Transformer was pre-trained using a resolution of 224x224  | :woman_scientist: | L | can | [MVTec Example] |


# Video 

# Time series

# Audio (high-frequency time series)
| Name | Description | Popularity | Effort | Training required | Resources |
| ---- | ----------- | ---------- | ------ | ----------------- | --------- |
| [OpenL3](https://github.com/marl/openl3) | OpenL3 is an open-source Python library for computing deep audio and image embeddings. | [![PyPI download month](https://img.shields.io/pypi/dm/openl3.svg)](https://pypi.python.org/pypi/openl3/) [![GitHub stars](https://img.shields.io/github/stars/marl/openl3.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/marl/openl3/stargazers/) | S | no | [[Github]](https://github.com/marl/openl3) [[Docs]](https://openl3.readthedocs.io/en/latest/?badge=latest) [[Example]](https://openl3.readthedocs.io/en/latest/tutorial.html#extracting-audio-embeddings) |
 [towhee](https://docs.towhee.io/User%20Guides/Built-in%20Pipelines/image-embedding/) | Towhee is a framework that provides ETL for unstructured data using SoTA machine learning models. | [![PyPI download month](https://img.shields.io/pypi/dm/towhee.svg)](https://pypi.python.org/pypi/towhee/) [![GitHub stars](https://img.shields.io/github/stars/towhee-io/towhee.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/towhee-io/towhee/stargazers/) | S | no | [[Github]](https://github.com/towhee-io/towhee) [[Docs]](https://docs.towhee.io/) [[Snippet]](https://towhee.io/towhee/audio-embedding-vggish) [[Example]](https://github.com/towhee-io/examples/tree/main/audio/audio_classification) |

# Geometry


# Multimodal



