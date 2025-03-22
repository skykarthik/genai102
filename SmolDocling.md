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