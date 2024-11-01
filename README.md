# Style Transfer

This repository contains a model for generating new images by combining the content of one image with the style of another. The results are saved in the `results` folder.

## Getting Started

### Requirements

To run the style transfer script, you will need the following Python packages:

```python
import torch
import torch.nn as nn
import torchvision
from torchvision import models, transforms
from PIL import Image
import numpy as np
import os


### Steps to Run the Script

1. **Set Up Paths:**
   - Specify the paths for your content and style images as well as the desired output path in the script.

2. **Run the Script:**
   - Execute the Python file to generate the stylized image.

### Example

Here’s a brief example of how to set the paths:

```python
content_image_path = 'path/to/content/image.jpg'
style_image_path = 'path/to/style/image.jpg'
output_image_path = 'path/to/output/image.jpg'
