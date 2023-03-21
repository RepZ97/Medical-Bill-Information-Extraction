Medical Bill Information Extractor project to automatically extract relevant information from medical bills using optical character recognition (OCR) technology, along with Google Tesseract, OpenCV2, and regular expressions. The system takes an input image of a medical bill and extracts important data such as patient name, provider name, service codes, and payment amounts, which can be used for further analysis and processing.

The project utilizes advanced computer vision techniques with OpenCV2 to preprocess the input image, which enhances the accuracy of OCR. Regular expressions are used to extract the relevant information from the text recognized by Tesseract OCR. The extracted information is then stored in a structured format, such as a JSON, for further use.

Overall, this project provides a convenient and efficient solution for the extraction of information from medical bills, which can significantly reduce the manual effort involved in this task. The project is available on GitHub, making it open-source and accessible for anyone to contribute and use.



Imported Libraries:

    import cv2
    from PIL import Image
    import numpy as np
    from pdf2image import convert_from_path
    import pytesseract
    from matplotlib import pyplot as plt
    import re
    import json

Installations:
    pdf2image, link:- https://pypi.org/project/pdf2image/
    pytesseract should be installed in the local enviorenment, link:- https://pypi.org/ project/pytesseract/
