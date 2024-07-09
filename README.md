<p align="center" style="width: 60%; height: 60%"><a href="https://www.medoid.ai/" target="_blank"><img src="https://www.medoid.ai/wp-content/uploads/2020/05/medoid-ai-logo-2.png" width="300px;" /></a></p>

# Blog post: A Hands-On Walkthrough on Model Quantization

## Table of contents
- [What?](#what)
- [Notebook](#notebook)
- [License](#license)

## What?
Quantization is a technique used to reduce the computational and memory overhead of a machine learning model by reducing the precision of the numbers used to represent the model's parameters. Typically, models use 32-bit floating-point numbers, but quantization converts these to 8-bit integers (or 4-bit integers). This can significantly reduce the model size and increase the inference speed, especially on CPUs and other hardware with limited computational resources. While this can lead to a slight reduction in model accuracy, the trade-off is often worthwhile for faster and more efficient deployments.

This GitHub repo contains the notebook from "[A Hands-On Walkthrough on Model Quantization](https://www.medoid.ai/blog/a-hands-on-walkthrough-on-model-quantization/)" blog post. This notebook demonstrates the process of quantizing and saving a Transformer model to improve the inference speed on a CPU and reduce the model size. 

## Notebook

Description | Link
--- | ---
A Hands-On Walkthrough on Model Quantization | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/medoidai/model-quantization-blog-notebooks/blob/main/notebooks/A_Hands_On_Walkthrough_on_Model_Quantization.ipynb)


## License

See our [LICENSE](LICENSE) for more details.
