# SmolDocling: Overview and Details

## Description
SmolDocling is an ultra-compact vision-language model specifically designed to execute end-to-end multi-modal document conversion. It combines vision and language processing to comprehensively interpret entire document pages, producing a new universal markup format called DocTags. These DocTags are capable of capturing all elements of a page in their full context along with location information.

## Features
- **Multi-modal Processing:** SmolDocling efficiently processes documents by simultaneously handling text, formulas, code, and charts.
- **OCR and More:** It is known for its robust document OCR, converting complex documents into structured, machine-readable data.
- **Fast Performance:** The model achieves rapid processing times of 0.35 seconds per page on consumer GPUs.
- **Versatile in Application:** Used for converting diverse document types with applications in scientific research (e.g., molecule structure prediction using SMILES), data digitization, and more.
- **Compact Model Size:** It features 256 million parameters which balance performance with model size.

## Usage
Developed with open-source philosophy, SmolDocling can be tried via demo spaces like Hugging Face. It is deployable using Python and transformers libraries, making it accessible for integration into various applications.

## Development and Collaboration
The library is a product of collaboration between IBM Research and Hugging Face, aiming to advance AI through open-source contributions and innovations.

## Key Applications
- Converting complex and varied document types into structured data.
- Efficiently handling and processing documents within machine learning and natural language processing frameworks.

## More Resources
- [Arxiv Abstract](https://arxiv.org/abs/2503.11576) – SmolDocling model description and technical details.
- [Hugging Face Preview](https://huggingface.co/ds4sd/SmolDocling-256M-preview) – Model's open-source preview and community discussions.
- [MarkTechPost Article](https://www.marktechpost.com/2025/03/18/ibm-and-hugging-face-researchers-release-smoldocling-a-256m-open-source-vision-language-model-for-complete-document-ocr/) – Industry insights and exploration of the SmolDocling library's potential.

*********

Here is an in-depth overview of the SmolDocling library based on various sources:

### 1. SmolDocling OCR App
- **Description**: This is a Streamlit application leveraging SmolDocling for advanced document OCR. It extracts text from document images and produces structured output in DocTags and Markdown formats.
- **Features**:
  - Supports single or multiple image processing.
  - Specialized document processing supports general conversion, table extraction, code and formula conversion, chart data extraction, and section header extraction.
  - Outputs can be saved for future use.
- **Requirements**:
  - Python 3.12+
  - Hugging Face account with an API token for model access.
- **Usage**:
  - The app is launched via Streamlit and accessible through a web interface.
- **Dependencies**:
  - Relies on Python libraries like streamlit, torch, transformers, etc.

### 2. docling_ocr Python Package
- **Overview**: A Python package utilizing SmolDocling for text extraction from images/documents using LLM models.
- **Features**:
  - LLM-powered context-aware extraction.
  - Multi-format support for scanned documents, forms, receipts, etc.
  - Batch processing capabilities.
- **Installation**:
  - Simple installation via pip (`pip install docling_ocr`).
- **Usage**:
  - Provides an easy API for document text extraction.
  - Supports GPU acceleration.
- **Comparison**: Leverages LLM capabilities, offering improvements over traditional OCR engines.

### 3. SmolDocling-256M WebUI
- **Description**: WebUI application for document conversion using SmolDocling models.
- **Features**:
  - Supports various devices (CPU/CUDA/MPS) for execution.
  - Various document format conversions including code and formulas.
- **Usage**:
  - Cloning the repository and running the application through Python scripts.

### 4. SmolDocling Wiki
- **Introduction**: A compact vision-language model developed for document conversion tasks, handling complex layouts and generating structured formats.
- **Architecture**:
  - Uses SmolVLM-256M and SmolLM-2 series for processing.
  - Employs DocTags for capturing page elements.
- **Performance**:
  - Efficient in processing, requiring low resources.
  - High accuracy in recognizing complex document elements.
- **Applications**:
  - Ideal for document digitization, data extraction, and automated processing.

### 5. SmolDocling-MLX
- **Web Application**: For converting document images using Gradio and docling-core library.
- **Features**:
  - Supports image input from various sources (URL, file, etc.).
  - Outputs can be provided in several formats.
  - Easy-to-use interface with Gradio.
- **Future Plans**:
  - Additional input formats and improved UI.

These descriptions provide a comprehensive overview of the SmolDocling tool's capabilities, applications, and infrastructure, highlighting its efficiency and versatility in document processing tasks.