# Medical Bill Information Extractor

## Project Overview

The Medical Bill Information Extractor is a project designed to automatically extract relevant information from medical bills using Optical Character Recognition (OCR) technology. This project leverages Google Tesseract, OpenCV2, and regular expressions to process and extract crucial data such as patient names, provider names, service codes, and payment amounts from input images of medical bills.

The extracted information is stored in a structured format (e.g., JSON) for further analysis and processing. This project aims to streamline the extraction process, significantly reducing the manual effort involved in handling medical bills.

## Features

- **OCR Technology**: Utilizes Google Tesseract for text recognition.
- **Image Processing**: Employs OpenCV2 for image preprocessing to enhance OCR accuracy.
- **Data Extraction**: Uses regular expressions to extract specific information from recognized text.
- **Structured Output**: Stores extracted data in structured formats such as JSON.
- **Open Source**: Available on GitHub for anyone to contribute and use.

## Requirements

To run this project, you need the following libraries and tools installed:

- `opencv-python`
- `Pillow`
- `numpy`
- `pdf2image`
- `pytesseract`
- `matplotlib`

## Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/RepZ97/Medical-Bill-Information-Extraction.git
    cd Medical-Bill-Information-Extraction
    ```

2. **Set Up a Virtual Environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Required Libraries**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Install `pdf2image`**:
    ```sh
    pip install pdf2image
    ```

5. **Install and Configure Tesseract OCR**:
    - Download and install Tesseract OCR from the following link: [pytesseract](https://pypi.org/project/pytesseract/).
    - Make sure Tesseract is added to your system's PATH.


## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with your improvements.

## License

This project is licensed under the [MIT License](LICENSE).