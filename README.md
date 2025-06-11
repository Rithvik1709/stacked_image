# Stacked Image 🔍

A lightweight Python/Jupyter notebook project demonstrating the stacking of multiple images (e.g., through blending, overlay, or grid arrangement). It includes a demo notebook and a sample image set for experimentation.

##  Repository Structure

stacked_image/
├── images/
│ └── ... # Sample input images for stacking
├── mcp.ipynb # Jupyter notebook demonstrating stacking techniques
├── README.md # Project overview and usage instructions


##  Features

- Load and display multiple images from a directory
- Stack images in various configurations:
  - Side-by-side
  - Top-to-bottom
  - Grid layout
  - Transparency/alpha blending
- Simple visualization directly inside a Jupyter notebook

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python libs ( `Pillow`, `matplotlib`, `numpy`)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Rithvik1709/stacked_image.git
   cd stacked_image
(Optional) Create a virtual environment:
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
Install dependencies:
 ```bash
pip install Pillow matplotlib numpy
```
Usage:
1-Launch the Jupyter notebook:
jupyter notebook mcp.ipynb
2-Explore cells to:
Load all images from images/
Select them into a list
Apply stacking methods (side-by-side, grid, overlay)
Visualize results inline
You can also adapt the notebook to:
Add new stacking approaches (e.g., collage, mosaic)
Handle different image sizes and formats
Save output images to file

### Use Cases

Quick collage/collation of image sets
Prototyping visual comparisons in data analysis
Educational demos on image manipulation
### Requirements

List actual requirements from the notebook, for example:

Pillow>=8.0
matplotlib>=3.3
numpy>=1.19

📄 License

This project is released under the MIT License. See LICENSE for details.

