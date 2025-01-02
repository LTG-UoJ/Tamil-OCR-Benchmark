# BoundingBox_Dataset, DiversePageFormats_Dataset, and LineSegmentation_Dataset

This repository contains datasets curated to advance research in Optical Character Recognition (OCR) and document image analysis, with a focus on low-resource languages like Tamil. These datasets include comprehensive annotations, ground truths, and metadata designed to evaluate system performance across diverse tasks, including:

- Diverse page formats and special categorizations
- Line-by-line segmentation
- Bounding-box segmentation

The datasets are structured to assess and evaluate the performance of OCR systems across a range of conditions, including  diverse page formats, varying noise levels, mono/multilingual text, and printing technologies.

## Repository Structure

### Datasets Overview
- **LineSegmentation_Dataset**
  - Contains data for line-level segmentation tasks.
  - Subdirectories:
    - `Ground truth texts`: Text files with ground truth information for each line.
    - `Line by line Cropped Images`: Cropped images corresponding to individual text lines.
    - `Source Images`: Original document images from which lines were extracted.

- **DiversePageFormats_Dataset**
  - Designed for diverse page format analysis.
  - Subdirectories:
    - `Images`: Document images in various page layouts and formats.
    - `Texts`: Associated text files for the corresponding document images.
    - `metadata_table.json`: Metadata providing details about the images and texts.

- **BoundingBox_Dataset**
  - Provides bounding box annotations for document elements.
  - Subdirectories:
    - `Bounding Boxes`: Contains bounding box annotations in a standardized format.
    - `Images`: Document images associated with bounding box annotations.
    - `Texts`: Ground truth text files related to the document images.

## Dataset Details

### LineSegmentation_Dataset
This dataset is curated for tasks involving the segmentation of text lines from document images. It includes:
- **Ground Truth Texts**: Textual content corresponding to each line.
- **Line by Line Cropped Images**: Individual cropped images for each line.
- **Source Images**: Original images used to generate the cropped lines and ground truths.

### DiversePageFormats_Dataset
This dataset supports experiments in handling diverse document page formats. It includes:
- **Images**: Document images with various layouts and page structures.
- **Texts**: Corresponding textual data extracted from the document images.
- **Metadata**: JSON file (`metadata_table.json`) containing metadata for each document image, such as file names, dimensions, and additional annotations.

### BoundingBox_Dataset
This dataset is targeted at tasks involving object detection and bounding box generation in document images. It includes:
- **Bounding Boxes**: Annotation files defining bounding boxes for elements in the document images.
- **Images**: Document images related to the bounding box annotations.
- **Texts**: Textual information corresponding to the bounding boxes and images.

## Usage

### Loading the Data
Each dataset can be accessed by navigating to its respective subdirectory. File formats and structures are consistent to facilitate integration into various workflows.

### Applications
- **LineSegmentation_Dataset**: Line segmentation tasks for OCR (Optical Character Recognition) and layout analysis.
- **DiversePageFormats_Dataset**: Testing and training models for handling diverse document layouts and page formats.
- **BoundingBox_Dataset**: Training object detection models to identify document elements based on bounding boxes.

## Metadata

The `metadata_table.json` file in the DiversePageFormats_Dataset provides structured metadata about the associated images and texts. It includes information such as:
- File names
- Image dimensions
- Associated textual data

## License
Open Access

## Citation
If you use these datasets in your research, please cite the repository as follows:

```plaintext
@dataset{your_dataset,
  author = {Your Name},
  title = {BoundingBox_Dataset, DiversePageFormats_Dataset, and LineSegmentation_Dataset},
  year = {2025},
  url = {https://github.com/your-repo-link}
}
```

## Acknowledgments
Thank you to all contributors and collaborators who supported the development and organization of these datasets.

## Contributing
We welcome contributions to improve and expand the datasets. If you have suggestions, corrections, or new data to contribute, please submit a pull request or open an issue.
