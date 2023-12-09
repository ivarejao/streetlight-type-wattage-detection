# Streetlight Type and Wattage Classifier

This repository implements an end-to-end classifier for intelligent detection of street lighting lamp types and wattages using a visual pre-trained transformer. The model is trained on a dataset containing image descriptors obtained from experiments using traditional machine learning models.

## Features

- **End-to-End Classification:** The repository provides a complete solution for classifying street lighting lamp types and estimating wattages.

- **Visual Pre-trained Transformer:** The model leverages a visual pre-trained transformer for enhanced feature extraction and classification accuracy.

- **Dataset Information:** Details about the dataset used for training the model, including image descriptors obtained from experiments using traditional machine learning models.

## Getting Started

Follow these steps to get started with the streetlight classifier:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/streetlight-classifier.git
   cd streetlight-classifier
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Classifier:**
   ```bash
   python classify_streetlights.py --image_path /path/to/your/image.jpg
   ```

## Dataset

The dataset used for training and evaluation is not included in this repository. Please refer to the paper ["A Transfer Learning Approach to Image-Based Intelligent Detection of Street Lighting Lamp Types and Wattages"] for details on accessing the dataset.

## Results

The model achieved promising results in terms of accuracy, precision, and recall. For detailed results, refer to the paper or the `results/` directory.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).
