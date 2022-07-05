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
 | [Vector Hub](https://github.com/RelevanceAI/vectorhub) | Vector Hub is a library for publication, discovery, and consumption of State-of-the-art models to turn data into vectors. | [![PyPI download month](https://img.shields.io/pypi/dm/vectorhub.svg)](https://pypi.python.org/pypi/vectorhub/) [![GitHub stars](https://img.shields.io/github/stars/RelevanceAI/vectorhub.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/RelevanceAI/vectorhub/stargazers/) | S | no | [[Github]](https://github.com/RelevanceAI/vectorhub) [[Quickstart]](https://github.com/RelevanceAI/vectorhub/blob/main/examples/Quickstart.ipynb) |
 | [Lightly](https://www.lightly.ai/) | Lightly is a computer vision framework for self-supervised learning. | [![PyPI download month](https://img.shields.io/pypi/dm/lightly.svg)](https://pypi.python.org/pypi/lightly/) [![GitHub stars](https://img.shields.io/github/stars/lightly-ai/lightly.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/lightly-ai/lightly/stargazers/) | M | yes | [[Docs]](https://docs.lightly.ai/) [[Github]](https://github.com/lightly-ai/lightly) |
| [ViT(Vision Transformer)](https://huggingface.co/google/vit-base-patch16-224) | Self-supervised Vision Transformer was pre-trained on ImageNet using a resolution of 224x224  | downloads: 75k/month | M | can | [[Docs]](https://huggingface.co/docs/transformers/model_doc/vit) [[Paper]](https://arxiv.org/pdf/2006.03677.pdf) |



# Video 
| Name | Description | Popularity | Effort | Training required | Resources |
| ---- | ----------- | ---------- | ------ | ----------------- | --------- |
| [OpenL3](https://github.com/marl/openl3) | OpenL3 is an open-source Python library for computing deep audio and image embeddings. | [![PyPI download month](https://img.shields.io/pypi/dm/openl3.svg)](https://pypi.python.org/pypi/openl3/) [![GitHub stars](https://img.shields.io/github/stars/marl/openl3.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/marl/openl3/stargazers/) | S | no | [[Github]](https://github.com/marl/openl3) [[Docs]](https://openl3.readthedocs.io/en/latest/?badge=latest) [[Example]](https://openl3.readthedocs.io/en/latest/tutorial.html#processing-video-files) |
[towhee](https://docs.towhee.io/) | Towhee is a framework that provides ETL for unstructured data using SoTA machine learning models. | [![PyPI download month](https://img.shields.io/pypi/dm/towhee.svg)](https://pypi.python.org/pypi/towhee/) [![GitHub stars](https://img.shields.io/github/stars/towhee-io/towhee.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/towhee-io/towhee/stargazers/) | S | no | [[Github]](https://github.com/towhee-io/towhee) [[Docs]](https://docs.towhee.io/) [[Example]](https://github.com/towhee-io/examples/tree/3a2207d67b10a246fd6a1654adf173d9902c3cf8/video/reverse_video_search) |

# Time series

# Audio (high-frequency time series)
| Name | Description | Popularity | Effort | Training required | Resources |
| ---- | ----------- | ---------- | ------ | ----------------- | --------- |
| [OpenL3](https://github.com/marl/openl3) | OpenL3 is an open-source Python library for computing deep audio and image embeddings. | [![PyPI download month](https://img.shields.io/pypi/dm/openl3.svg)](https://pypi.python.org/pypi/openl3/) [![GitHub stars](https://img.shields.io/github/stars/marl/openl3.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/marl/openl3/stargazers/) | S | no | [[Github]](https://github.com/marl/openl3) [[Docs]](https://openl3.readthedocs.io/en/latest/?badge=latest) [[Example]](https://openl3.readthedocs.io/en/latest/tutorial.html#extracting-audio-embeddings) |
 [towhee](https://docs.towhee.io/User%20Guides/Built-in%20Pipelines/image-embedding/) | Towhee is a framework that provides ETL for unstructured data using SoTA machine learning models. | [![PyPI download month](https://img.shields.io/pypi/dm/towhee.svg)](https://pypi.python.org/pypi/towhee/) [![GitHub stars](https://img.shields.io/github/stars/towhee-io/towhee.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/towhee-io/towhee/stargazers/) | S | no | [[Github]](https://github.com/towhee-io/towhee) [[Docs]](https://docs.towhee.io/) [[Snippet]](https://towhee.io/towhee/audio-embedding-vggish) [[Example]](https://github.com/towhee-io/examples/tree/main/audio/audio_classification) |
  | [Vector Hub](https://github.com/RelevanceAI/vectorhub) | Vector Hub is a library for publication, discovery, and consumption of State-of-the-art models to turn data into vectors. | [![PyPI download month](https://img.shields.io/pypi/dm/vectorhub.svg)](https://pypi.python.org/pypi/vectorhub/) [![GitHub stars](https://img.shields.io/github/stars/RelevanceAI/vectorhub.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/RelevanceAI/vectorhub/stargazers/) | S | no | [[Github]](https://github.com/RelevanceAI/vectorhub) [[Quickstart]](https://github.com/RelevanceAI/vectorhub/blob/main/examples/Quickstart.ipynb) |

# Geometry


# Multimodal



