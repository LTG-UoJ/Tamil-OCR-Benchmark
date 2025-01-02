# BoundingBox_Dataset, DiversePageFormats_Dataset, and LineSegmentation_Dataset

This repository contains datasets curated to advance research in Optical Character Recognition (OCR) and document image analysis, with a focus on low-resource languages like Tamil. These datasets include comprehensive annotations, ground truths, and metadata designed to evaluate system performance across diverse tasks, including:

- Diverse page formats and special categorizations
- Line-by-line segmentation
- Bounding-box segmentation

The datasets are structured to assess and evaluate the performance of OCR systems across a range of conditions, including  diverse page formats, varying noise levels, mono/multilingual text, and printing technologies.

## Repository Structure

### Datasets Overview
- **LineSegmentation_Dataset**
  - Contains data of line-level segmentation.
  - Subdirectories:
    - `Ground truth texts`: Text files with ground truth information for each line.
    - `Line by line Cropped Images`: Cropped images corresponding to individual text lines.
    - `Source Images`: Original document images from which lines were extracted.

- **DiversePageFormats_Dataset**
  - Designed for diverse page format analysis.
  - Subdirectories:
    - `Images`: Document images in various page formats.
    - `Texts`: Associated text files for the corresponding document images.
    - `metadata_table.json`: Metadata providing details about the images and texts.

- **BoundingBox_Dataset**
  - Provides bounding box segmentation dataset.
  - Subdirectories:
    - `Bounding Boxes`: Contains bounding box annotations in a standardized format.
    - `Images`: Document images associated with bounding box annotations.
    - `Texts`: Ground truth text files related to the document images.

## Usage

## Metadata

The `metadata_table.json` file in the DiversePageFormats_Dataset provides structured metadata about the associated images and texts. It includes information such as:
- Image Information: Contains details about the image format, memory size, resolution, sheet color, image condition, width, and height.
- Data Information: Attributes such as font style, font size, resource type, script, number of languages, genre, domain, and content format.
- Data Source Information: Provides context about the document’s origin and historical background, supporting traceability such as title, subtitle, alternative title, parallel title, author, publisher, edition, year, printing place, type of material, printing technology, ISBN/ISSN, and Copyright.

## License
Open Access

## Acknowledgments
Thank you to all contributors and collaborators who supported the development and organization of these datasets.

## Contributing
We welcome contributions to improve and expand the datasets. If you have suggestions, corrections, or new data to contribute, please submit a pull request or open an issue.
