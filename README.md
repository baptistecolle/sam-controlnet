# Conditioning Stable Diffusion with Segment Anything

Please view our [blog post](https://sam-controlnet.notion.site/Conditioning-Stable-Diffusion-with-Segment-Anything-8a605e997002487ca259646e6adc1ae4?pvs=4) for details about our project

Notebooks contains the 3 main notebook used during our project.

The notebook should be run in that order
1) Sam-Controlnet-Dataset
2) Sam-Controlnet-Train
3) Sam-Controlnet-Eval

This create a custom controlnet trained on the segment anything model
It is then possible to use that controlnet model to condition stable diffusion with segmentation masks
