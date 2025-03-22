**Teacher-Student Behavior Recognition Dataset**

---

## Dataset Overview

Welcome to the Teacher-Student Behavior Recognition Dataset! This dataset is designed for action recognition tasks in computer vision, specifically targeting student behaviors in classrooms. The dataset includes 3,500 high-resolution images covering seven common classroom behaviors: looking up, using a phone, sleeping, writing, chatting, and standing. Each behavior has 500 images, extracted from 100 different classroom videos. Additionally, we provide the original 100 classroom videos to facilitate further research and analysis.

---

## Dataset Structure

The dataset is organized as follows:

- **images/**: Contains 3,500 labeled student behavior images in JPG format.
- **labels/**: Contains corresponding YOLO format annotation files, specifying behavior categories and bounding box positions.
- **videos/**: Contains 100 original classroom videos for additional analysis.

---

## Dataset Application & Usage Guide

This dataset requires an application before use due to privacy concerns, as it contains classroom footage that may include personally identifiable information. To request access, please send an email to 806671633@qq.com with your name, institution, research area, and intended use. Upon approval, we will provide access to download the dataset.
### Steps to Use the Dataset

1. **Dataset Application**: Send an application email to **[806671633@qq.com](mailto:806671633@qq.com)**.
2. **Download & Extraction**: Upon approval, download and extract the dataset to your local directory.
3. **Data Loading**: Use the YOLO framework to load images from `images/` and labels from `labels/`.
4. **Model Training**: Configure training parameters as per the YOLO framework guidelines and begin training your model.

---

## Dataset Features

- **Diversity**: The images are extracted from 100 different classroom videos, covering various learning environments and behaviors.
- **High-Quality Annotations**: Every image is carefully annotated to ensure accuracy and consistency.
- **YOLO-Compatible**: The annotations follow the YOLO format, making them ready for use in YOLO-based models.
- **Rich Behavior Categories**: Includes seven common student classroom behaviors, representing typical classroom scenarios.

---

## Dataset Categories

This dataset contains the following seven behavior categories:

1. Hands Up
2. Using Phone
3. Sleeping
4. Writing
5. Chatting
6. Standing

---

## Annotation Format

The annotation files follow the YOLO format, with each line representing an annotated behavior in the following structure:

Where:

- `<class_id>`: The index of the behavior category (0 to 6).
- `<x_center>`, `<y_center>`: The normalized coordinates of the bounding box center.
- `<width>`, `<height>`: The normalized width and height of the bounding box.

---

## License

This dataset follows the **MIT License**. Please ensure compliance with the license terms when using this dataset.

---

## Contributions & Feedback

We welcome any contributions or feedback regarding the dataset! If you discover errors or have suggestions for improvements, please contact us via **GitHub Issues** or **Pull Requests**.

---

## Acknowledgments

We sincerely appreciate the efforts of everyone involved in building and annotating this dataset. Your contributions have made this research possible!



