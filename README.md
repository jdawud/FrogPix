# FrogPix
Frog images for ML model training

🐸

Overview
This repository aims to build a high-quality, open-source dataset of frog images for research and machine learning projects. The dataset aims to cover a broad range of frog species and is open for contributions from anyone interested in amphibian research or computer vision.

Goals
To create a comprehensive database of labeled frog images.
To encourage community participation in building a reliable dataset.
To facilitate the development of machine learning models, especially those focused on biodiversity and conservation.


How to Contribute

Guidelines
Quality: Images should be clear and high-resolution.
Labeling: Please follow the directory structure and metadata guidelines detailed below.
Legality: Ensure you have the rights to the images you are contributing.

Steps
1. Fork this repository.
2. Add your images to the appropriate folder in the directory structure.
3. Add metadata for your images in the corresponding JSON file.
4. Create a pull request with your contributions.

Directory Structure

Frog-Image-Dataset/
│
├── species_a/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── metadata.json
│
├── species_b/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── metadata.json
│
└── ...

Metadata
Each species folder contains a metadata.json file with labeling information for the images. An example metadata entry is shown below:

{
  "image1.jpg": {
    "common_name": "American Bullfrog",
    "scientific_name": "Rana catesbeiana"
  },
  "image2.jpg": {
    "common_name": "Green Tree Frog",
    "scientific_name": "Hyla cinerea"
  }
}

License
This dataset is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0). By contributing to this repository, you agree to abide by its terms. See the LICENSE file for more details.
