# HieroGlyphCo

HieroGlyphCo is a computer vision and OCR-based translation system designed to recognize handwritten or printed English text and convert it into corresponding Hieroglyphic symbols. The project combines optical character recognition techniques with image-based glyph generation to explore the intersection of artificial intelligence, language processing, and Egyptian cultural heritage preservation.

## Features

* Detects handwritten and printed English text from images
* Converts detected text into Hieroglyphic symbols
* Supports multiple Hieroglyphic rendering styles
* Integrates OCR and image processing techniques
* Interactive user interface using Gradio
* Image-based Hieroglyphic generation pipeline

## Technologies Used

* Python
* EasyOCR
* PaddleOCR
* OpenCV
* Gradio
* NumPy
* Pillow (PIL)
* Hugging Face
* Computer Vision Techniques

## Project Workflow

1. Upload an image containing English text
2. OCR model extracts the text from the image
3. Extracted characters are mapped to corresponding Hieroglyphic symbols
4. Hieroglyphic glyph images are generated and concatenated
5. Final translated Hieroglyphic output is displayed

## Directory Structure

```bash
HieroGlyphCo/
│
├── HieroGlyphCo_OCR_Translator.ipynb
├── requirements.txt
├── README.md
│
├── hieroglyphics/
│   ├── Style1/
│   ├── Style2/
│   ├── Style3/
│   └── Style4/
│
├── sample_images/
├── screenshots/
```

## Installation

Clone the repository:

```bash
git clone https://github.com/monikasameer1/HieroGlyphCo.git
cd HieroGlyphCo
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook or launch the Gradio application.

## Example Use Cases

* Educational tools for learning Hieroglyphics
* Cultural heritage visualization
* OCR experimentation and comparison
* AI-powered translation demonstrations
* Computer vision research projects

## Challenges

The project involved handling OCR accuracy variations across different handwriting styles and managing compatibility issues between OCR frameworks and modern Python environments.

## Future Improvements

* Custom-trained OCR model
* GAN-based handwriting style transfer
* Real-time translation support
* Expanded Hieroglyphic dataset
* Improved symbol alignment and rendering
* Web deployment

## Author

Monika Sameer Danial Abdelshahid

Computer Engineering Graduate – German University in Cairo (GUC)
