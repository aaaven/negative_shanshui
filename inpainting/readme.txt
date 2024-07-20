# Inpainting Part

## Prerequisites
- [Anaconda](https://www.anaconda.com/products/distribution)
- Python 3.8
- CUDA 11.8


### Create the conda environment
```bash
conda env create -f environment.yaml
```

### Activate the environment
```bash
conda activate linz24
```

### Install CUDA and PyTorch
Follow the instructions on the [PyTorch website](https://pytorch.org/) to install the correct version of PyTorch with CUDA 11.8 support. Example command:
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

## Usage

### Run the notebook
The main script for this project is `full_cv2show.ipynb`. Open and run it using Jupyter Notebook:
```bash
jupyter notebook full_cv2show.ipynb
```

### Visualization
Visualization is performed using OpenCV. Note that this can cause the display speed to slow down due to the high resolution of 2000x3000.

### Local Model Files
- `sdxl_turbo`: Folder containing local model files ready for use.
- `mask_design`: Folder containing masks designed in Photoshop.

## Requirements
The original method requirements are listed in `requirements.txt`. However, by using `environment.yaml`, you do not need to manually install these requirements. The `requirements.txt` is provided as a backup.

## Contributing
Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License.
```

### 项目目录结构
确保你的项目文件结构如下：

```
ExampleProject/
├── environment.yaml
├── README.md
├── full_cv2show.ipynb
├── sdxl_turbo/
│   └── (model files)
├── mask_design/
│   └── (mask files)
├── requirements.txt
└── other project files
```

希望这些内容对你有帮助！如果你有任何其他问题，请随时告诉我。